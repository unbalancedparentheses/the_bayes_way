# The Bayes Way [![Build Status](https://travis-ci.org/unbalancedparentheses/the_bayes_way.svg?branch=master)](https://travis-ci.org/unbalancedparentheses/the_bayes_way)

The Bayes Way - this page - is a small subset of the best articles, papers, videos and books to learn Probability and Statistics. It is a way to reduce the signal-noise ratio for beginners.

# Not yet reviewed

> These resources were recently found and have not been reviewed yet.

### Books
- [Bayesian Modeling and Computation in Python - Martin, Kumar, Lao (2022)](https://bayesiancomputationbook.com) - Hands-on guide covering PyMC, ArviZ, BART; free online
- [Bayes Rules! An Introduction to Applied Bayesian Modeling - Johnson, Ott, Dogucu (2022)](https://www.bayesrulesbook.com) - Accessible undergraduate intro; free online
- [Probabilistic Machine Learning: An Introduction - Kevin Murphy (MIT Press, 2022)](https://probml.github.io/pml-book/book1.html) - Modern ML unified under probabilistic/Bayesian modeling; free PDF

### Courses
- [Statistical Rethinking 2023 Lectures - Richard McElreath](https://youtube.com/playlist?list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus) - 20-lecture YouTube course; PyMC5 translations available
- [BDA Course (Aalto) - Aki Vehtari (2024)](https://avehtari.github.io/BDA_course_Aalto/) - Full university course based on BDA3; free
- [Learning Bayesian Statistics Podcast - Alexandre Andorra](https://www.learnbayesstats.com/) - 175+ episodes interviewing Bayesian researchers

### Tools
- [PyMC v5 (2023)](https://www.pymc.io) - Major rewrite on PyTensor; [paper](https://peerj.com/articles/cs-1516/)
- [NumPyro](https://num.pyro.ai) - JAX-based PPL with JIT-compiled NUTS/HMC; GPU/TPU compatible
- [BlackJAX](https://github.com/blackjax-devs/blackjax) - Composable JAX library of MCMC/VI samplers

### Papers
- [Bayesian Workflow - Gelman, Vehtari, Simpson et al. (2020)](https://arxiv.org/abs/2011.01808) - Authoritative 70+ page treatment of the full Bayesian modeling cycle
- [Pathfinder: Parallel Quasi-Newton Variational Inference (JMLR, 2022)](https://jmlr.org/papers/v23/21-0889.html) - Fast VI algorithm outperforming ADVI by 1-2 orders of magnitude; now in Stan and PyMC
- [The Frontier of Simulation-Based Inference - Cranmer, Brehmer, Louppe (PNAS, 2020)](https://www.pnas.org/doi/10.1073/pnas.1912789117) - Landmark review of likelihood-free inference methods

### Tutorials
- [Probabilistic Programming with PyMC - Chris Fonnesbeck (2024)](https://github.com/fonnesbeck/probabilistic_python) - Workshop notebooks covering PyMC5 workflow
- [ArviZ: Exploratory Analysis of Bayesian Models](https://arviz-devs.github.io/EABM/) - Interactive notebooks on posterior checks, LOO-CV, diagnostics

## Introduction to Python, Numpy and Pandas

- [A Whirlwind Tour of Python - Jake VanderPlas](https://github.com/jakevdp/WhirlwindTourOfPython) - Fast-paced beginner overview of Python syntax and core language features for those coming from other languages
- [Python Data Science Handbook - Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/) - Comprehensive guide to NumPy, Pandas, Matplotlib, and Scikit-Learn for data analysis; free online
- [From Python to Numpy - Nicolas P. Rougier](http://www.labri.fr/perso/nrougier/from-python-to-numpy/) - Teaches how to replace slow Python loops with fast vectorized NumPy operations; intermediate level
- [100 numpy exercises - Nicolas P. Rougier](https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises.md) - Graded drill set from beginner to advanced for building NumPy fluency through practice
- [A Concrete Introduction to Probability (using Python) - Peter Norvig](https://github.com/norvig/pytudes/blob/master/ipynb/Probability.ipynb) - Notebook that builds probability intuition by coding classic problems from scratch in Python

## Introduction to Probability and Statistics (videos and books)

- [Khan Academy's statistics and probability course](https://www.khanacademy.org/math/statistics-probability) - Free video-based course covering distributions, confidence intervals, hypothesis testing, and regression from scratch; beginner level
- [Bayesian Statistics the Fun Way - Will Kurt](https://nostarch.com/learnbayes) - Lighthearted beginner introduction to Bayesian thinking with minimal math prerequisites
- [Think Stats - Allen B. Downey](https://www.goodreads.com/book/show/12042357-think-stats) - Teaches classical statistics through Python code and real datasets rather than formulas; beginner level
- [Think Bayes - Allen B. Downey](https://www.goodreads.com/book/show/18711042-think-bayes) - Introduces Bayesian statistics computationally using Python, making concepts concrete through simulation; beginner level
- [The Art of Data Science: A Guide for Anyone Who Works with Data - Roger D. Peng, Elizabeth Matsui](https://www.goodreads.com/book/show/26299386-the-art-of-data-science) - Short practical guide to the iterative process of asking questions, exploring data, and building models; beginner level
- [Statistics Done Wrong - Alex Reinhart](https://www.goodreads.com/book/show/23241062-statistics-done-wrong) - Catalogues the most common statistical mistakes in research and how to avoid them; essential reading for any practitioner

## Probabilistic Programming

- [Probabilistic Programming & Bayesian Methods for Hackers - Cam Davidson-Pilon](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) - Computation-first introduction to Bayesian methods using PyMC; free online book ideal for programmers with little stats background
- [Bayesian Analysis with Python - Osvaldo Martin](https://www.packtpub.com/big-data-and-business-intelligence/bayesian-analysis-python-second-edition) - Practical guide to building and interpreting Bayesian models with PyMC and ArviZ; intermediate level

## MOOCs

- [Harvard's Statistics 110: Probability](https://projects.iq.harvard.edu/stat110/home) - Rigorous undergraduate probability course by Joe Blitzstein covering combinatorics, random variables, and distributions; intermediate level
- [Duke's Statistics with R Specialization](https://www.coursera.org/specializations/statistics) - Five-course Coursera sequence covering inference, regression, and Bayesian statistics using R; beginner to intermediate
- [MITx's Statistics and Data Science MicroMasters](https://www.edx.org/micromasters/mitx-statistics-and-data-science) - Graduate-level program covering probability, inference, machine learning, and causal analysis; intermediate to advanced

## Books

- [Introduction to Probability - Joseph K. Blitzstein, Jessica Hwang](https://www.goodreads.com/book/show/21558327-introduction-to-probability) - Thorough undergraduate probability textbook with rich examples and intuitive explanations; companion to Harvard's Stat 110; intermediate level
- [A Student's Guide to Bayesian Statistics - Ben Lambert](https://www.goodreads.com/book/show/39784111-a-student-s-guide-to-bayesian-statistics) and [its video lectures](https://www.youtube.com/playlist?list=PLwJRxp3blEvZ8AKMXOy0fc0cqT61GsKCG) - Bridges the gap between introductory and advanced Bayesian texts by explaining the math behind MCMC and variational methods; intermediate level
- [A First Course in Bayesian Statistical Methods - Peter D. Hoff](https://www.goodreads.com/book/show/7651231-a-first-course-in-bayesian-statistical-methods) - Concise graduate-level introduction covering conjugate priors, hierarchical models, and MCMC with R examples; intermediate level
- [Doing Bayesian Data Analysis: A Tutorial Introduction with R - John K. Kruschke](https://www.goodreads.com/book/show/9003187-doing-bayesian-data-analysis) - Gentle and thorough hands-on guide to Bayesian analysis using R and JAGS, known as the "puppy book"; beginner to intermediate
- [Statistical Rethinking - Richard McElreath](https://xcelab.net/rm/statistical-rethinking/) and [Statistical Rethinking Winter 2019 video lectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI) - Builds Bayesian modeling intuition through causal thinking and simulation with outstanding video lectures; intermediate level
- [Probability Theory: The Logic of Science - E.T. Jaynes](https://www.goodreads.com/book/show/151848.Probability_Theory) and [Aubrey Clayton lectures on the key chapters of Probability Theory The Logic of Science](https://www.youtube.com/playlist?list=PL9v9IXDsJkktefQzX39wC2YG07vw7DsQ_) - Foundational treatise arguing probability is an extension of logic, deeply influential on Bayesian philosophy; advanced level
- [Bayesian Data Analysis - Andrew Gelman](http://www.stat.columbia.edu/~gelman/book/) - The definitive graduate reference on Bayesian methods covering hierarchical models, MCMC diagnostics, and model checking; advanced level
- [Information Theory, Inference and Learning Algorithms - David J.C. MacKay](https://www.goodreads.com/book/show/201357.Information_Theory_Inference_and_Learning_Algorithms) - Unifies information theory, Bayesian inference, and machine learning with clear derivations and exercises; free online; intermediate to advanced
- [Statistical consequences of fat tails - Nassim Taleb](https://www.academia.edu/37221402/STATISTICAL_CONSEQUENCES_OF_FAT_TAILS_TECHNICAL_INCERTO_COLLECTION_) - Shows why standard statistical tools break under heavy-tailed distributions and what to use instead; advanced level

## Science popularization

- [The Signal and the Noise: Why So Many Predictions Fail - But Some Don't - Nate Silver](https://www.goodreads.com/book/show/13588394-the-signal-and-the-noise) - Explores why most forecasts fail and how Bayesian thinking improves prediction in politics, sports, and economics; beginner level
- [The Theory That Would Not Die: How Bayes' Rule Cracked the Enigma Code, Hunted Down Russian Submarines, and Emerged Triumphant from Two Centuries of Controversy - Sharon Bertsch McGrayne](https://www.goodreads.com/book/show/10672848-the-theory-that-would-not-die) - Narrative history of Bayes' theorem and the people who championed it through centuries of controversy; beginner level

## Papers and Thesis

- [It is a 10 sigma event or are you wrong about the world? - Nassim Taleb](https://youtu.be/k_lYeNuBTE8) - Talk arguing that extreme "sigma" events reveal flawed distributional assumptions rather than rare outcomes
- [The Law of Large Numbers and Fat Tailed Distributions - Nassim Taleb](https://youtu.be/nDY_fh2TVlI) - Talk explaining why the law of large numbers converges far more slowly under fat-tailed distributions
- [On the statistical properties and tail risk of violent conflicts - Pasquale Cirillo, Nassim Nicholas Taleb](https://arxiv.org/abs/1505.04722) - Applies extreme value theory to war casualties, showing that violence follows heavy-tailed power laws
- [Automating Inference, Learning, and Design using Probabilistic Programming - Tom Rainforth](http://www.robots.ox.ac.uk/~twgr/assets/pdf/rainforth2017thesis.pdf) - Oxford PhD thesis providing a rigorous theoretical foundation for probabilistic programming and automated inference
- [A Conceptual Introduction to Hamiltonian Monte Carlo](https://arxiv.org/abs/1701.02434) - Builds geometric intuition for HMC sampling without heavy math, essential for understanding modern MCMC
- [The Markov Chain Monte Carlo Revolution - Persi Diaconis](https://math.uchicago.edu/~shmuel/Network-course-readings/MCMCRev.pdf) - Accessible survey of how MCMC transformed applied mathematics, statistics, and scientific computing
