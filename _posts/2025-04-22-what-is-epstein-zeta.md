---
title: 'What does the Epstein zeta function actually do?'
date: 2025-04-22
permalink: /posts/2025/04/what-does-epstein-zeta-do/
tags:
  - math
  - physics
  - history
  - number theory
  - casimir effect
  - Epstein Zeta function
---

When I first started studying mathematics at university, I was obsessed with popular math problems, such as the Riemann Hypothesis. The conjecture states that all zeros of the Riemann zeta function other than \\(-2, -4, -6\\), ... lie on the critical line \\(\operatorname{Re}(z) = 1/2\\). If proven, this would earn you a million dollars 💸

Unfortunately, I feel my chances of winning that prize are better by playing the lottery[^1] 🍀 so thankfully, I'm not working on this problem.

However, my research is somewhat related. The **Epstein zeta function**, derived in 1903[^2][^3] by the Jewish mathematician **Paul Epstein**, generalizes the Riemann zeta function to higher dimensions. Epstein, who later committed suicide in fear of persecution by the Gestapo, already derived most of the results we are working with today. This is incredibly impressive, and his work deserves to be more widely recognized, which is one of my reasons for writing this.

You can actually see these trivial zeros \\(-2, -4, -6\\) of the Riemann zeta function in the plot of the blue line (Epstein zeta at \\(x = y = 0\\) and lattice \\(\mathbb{Z}\\) = Riemann zeta). Note that the Epstein zeta function shares these zeros for other values of \\(x\\) too!

![Plot of the Epstein zeta function]({{ site.baseurl }}/images/2025-04-22-zetanuplot.png)
*Plot of the one-dimensional Epstein zeta function as a function of the exponent \\(\nu\\) for \\(y = 0\\) and various values of \\(x\\). Created by the author. This image is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).*

Interestingly, the Epstein zeta function isn’t just relevant to number theory (the research area where the Millennium Problem is situated). It also plays a crucial role in physics, particularly in systems involving sums over large numbers of particles. One notable example is the **Casimir effect**, which was predicted in 1948[^4] and later experimentally confirmed. The reason for this is quite technical; you might encounter it after about six semesters of studying physics, in an introduction to quantum field theory at university. Surprisingly, the calculation can be expressed in terms of the Epstein zeta function!

Here’s how it works: Imagine two perfectly conducting plates in a vacuum, placed extremely close to each other. Classical physics predicts that nothing will happen since it’s a vacuum. But in the realm of quantum physics, the opposite is true: quantum fluctuations cause an attractive force between the plates, effectively pushing them together. This result is truly surprising and counterintuitive, since intuition says that there is nothing in the vacuum to act on the plates! The underlying calculation involves advanced techniques, but at its core, it can be expressed using the Epstein zeta function. This is just one example of how my favorite special bridges the gap between abstract theory and real-world phenomena ✨

So, why does this matter for researchers in physics? Before our work, if someone wanted to calculate the Epstein zeta function for a specific physical scenario, they would likely have to sift through expensive, specialized books on lattice sums (such as this one[^5]), hoping to find a relevant case 😓 Now, we’ve solved this problem by developing a free, open-source software library[^6] that efficiently calculates the Epstein zeta function for any real parameter 🚀 In our preprint[^7], we discuss the properties of this function and how it can be applied to a variety of physical systems.

![Paul Epstein]({{ site.baseurl }}/images/2025-04-22-Epstein.png)
*Paul Epstein (1871–1939), the mathematician who derived the Epstein zeta function. Image source: [MacTutor History of Mathematics archive](https://mathshistory.st-andrews.ac.uk/Biographies/Epstein_Paul/), University of St Andrews, Scotland. This image is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).*

[1] Video: [Riemann Hypothesis - Numberphile](https://www.youtube.com/watch?v=d6c6uIyieoo) "The most difficult way to earn a million dollars"

[2] P. Epstein. “Zur Theorie allgemeiner Zetafunctionen”. In: Math. Ann. 56
(1903), pp. 615–644. url: https://doi.org/10.1007/BF01444309.

[3] P. Epstein. “Zur Theorie allgemeiner Zetafunktionen. II”. In: Math. Ann. 63
(1906), pp. 205–216. url: https://doi.org/10.1007/BF01449900.

[4] Hendrik BG Casimir. “On the attraction between two perfectly conducting
plates”. In: Indag. Math. 10.4 (1948), pp. 261–263.

[5] J. Borwein et al. Lattice Sums Then and Now. Encyclopedia of Mathematics
and its Applications. Cambridge University Press, 2013. url: https://doi.
org/10.1017/CBO9781139626804.

[6] https://github.com/epsteinlib/epsteinlib

[7] Andreas A Buchheit, Jonathan K. Busse, and Ruben Gutendorf. “Computation
and properties of the Epstein zeta function with high-performance implemen-
tation in EpsteinLib”. In: arXiv preprint arXiv:2412.16317 (2024).
