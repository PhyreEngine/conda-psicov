This repository contains a [conda][conda] recipe for building [psicov][ps], a
tool for the prediction of residue-residue contacts via correlated mutations.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `./build`.
This recipe will build several variants, one for each supported CPU
architecture.

[conda]: https://conda.io
[miniconda]: https://conda.io/miniconda.html
[ps]: http://bioinfadmin.cs.ucl.ac.uk/downloads/PSICOV/
