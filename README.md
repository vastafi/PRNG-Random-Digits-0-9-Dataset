# PRNG Random Digits Dataset

This repository contains pseudo-random digit sequences in the range 0–9, generated from 10 different sources.  
Each source includes **6 independent runs**, and **each file contains exactly 2,614,690 digits**.

## Sources
- C++ `rand()` from `<cstdlib>`
- Excel `=RANDBETWEEN(0,9)`
- Java `SecureRandom`
- Java `ThreadLocalRandom`
- Mathematica `RandomInteger`
- Pi (sequential decimal digits of π, downloaded from https://calculat.io/en/number/download-pi-digits-files-txt-zip)
- Python `numpy.random.default_rng`
- Python `secrets`
- R `sample(0:9)`
- Random.org (atmospheric noise)

## Purpose
Suitable for:
- Uniformity analysis
- Goodness-of-fit testing (χ², KS, etc.)
- Autocorrelation and independence checks
- Cross-PRNG quality comparison
