# cgibbs.jl

Companion Julia module for CLIMB R package

**NOTE: this package was developed in Julia v1.0.2, and likely is not back-compatible with older versions. It has been tested to be compatible with v1.5.3, as well as the experimental (as of 07/23/2022) v1.8.0 for macOS ARM for M-series processors**

## Installation

To install, launch Julia, then enter the following:

```{julia}
using Pkg
Pkg.add(PackageSpec(url="https://github.com/hillarykoch/cgibbs.jl"))
```

Load and test the package by then executing the following from inside Julia (optional):
```{julia}
using cgibbs
Pkg.test("cgibbs")
```
If things went as they should, you should see something akin to this:
```console
Testing cgibbs

Running the MCMC... 100%|███████████████████████████|

Test Summary:                  | Pass  Total
reasonable parameter estimates |   19     19
Test Summary:                                          | Pass  Total
adaptively tuning proposal degrees of freedom properly |    2      2
Test Summary:            | Pass  Total
unbiased random matrices |   11     11
Test Summary:                         | Pass  Total
0 and 1 constraints correctly imposed |    7      7
   Testing cgibbs tests passed 
```


---------------------------------------------------------------------------------------------------------------------------------------

---------------------------------------------------------------------------------------------------------------------------------------
