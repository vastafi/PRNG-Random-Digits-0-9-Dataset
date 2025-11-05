# PRNG Random Digits Dataset

This repository contains pseudo-random digit sequences in the range 0–9, generated from 10 different sources.  
Each source includes **6 independent runs**, and **each file contains exactly 2,614,690 digits**.

## Sources
- C++ `std::mt19937`
- Excel `RAND()`
- Java `SecureRandom`
- Java `ThreadLocalRandom`
- Mathematica `RandomInteger`
- Pi (sequential decimal digits)
- Python `numpy.random.default_rng`
- Python `secrets`
- R `runif()`
- Random.org (atmospheric noise)

## Purpose
Suitable for:
- Uniformity analysis
- Goodness-of-fit testing (χ², KS, etc.)
- Autocorrelation and independence checks
- Cross-PRNG quality comparison
