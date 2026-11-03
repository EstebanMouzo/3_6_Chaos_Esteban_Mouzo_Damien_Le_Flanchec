# 3.6. Disorder in spatially extended systems

This repository contains project 3.6. for the computational physics course PHY51171, done by Esteban Mouzo and Damien Le Flanchec.

## Goals of the project

This project consists in studying the rich physics of transition to disorder for spatially extended
systems. A prototypical amplitude equation (the Ginzburg-Landau equation studied at the end
of tutorial 3 in one dimension) describes a large amount of phenomena occurring in unstable
systems, from nonlinear waves to phase transitions, from chemical reactions, superconductivity,
superfluidity, and Bose-Einstein condensates to liquid crystals and strings in field theory. The
goal of this project consists in investigating different regimes described by the complex Ginzburg-
Landau equation (CGLE) in two spatial dimensions. A combination of algorithms presented
during the lecture on advection-diffusion equations can be used to build a code solving the
CGLE.

A pseudo-spectral method with an exponential time differencing scheme is well suited, and its
accuracy should be checked first, for instance on the Benjamin-Feir instability of plane waves,
whose growth rate is known analytically. The main goal is then to reconstruct the phase diagram
of Chaté and Manneville: phase turbulence, defect turbulence, frozen states of spirals, and the
transitions between them. These regimes can be characterized quantitatively by the density of
topological defects, the correlation length and the spectrum of Lyapunov exponents, which gives
access to the dimension of the chaotic attractor. Finally, one can look at the dynamics of spiral
waves, which are observed in chemical reactions and in the heart, and at their interactions.

## Repository layout

```
.
├── design/                  exploration and prototyping
│   └── 
├── production/              code that generates the data
│   ├── chaos/             the simulation library
│   │   ├── 
├── results/                 raw output of the production scripts (text tables)
├── analysis/                scripts that turn results into figures
├── figures/                 figures and numbers included in the report
├── report/                  LaTeX source of the report
├── tests/                   unit tests (pytest)
└── Makefile                 shortcuts to reproduce everything
```

## Installation

...

## Usage

```bash
...
```