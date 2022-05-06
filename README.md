# scipy-ci-artifacts

This repository is intended for use by the scipy/scipy repository continuous integration
tests. We reserve the right to delete any files in this repository or the entire repository.

## openblas binary for windows

This binary is for a get-it-working-fast build needed when porting the Scipy build to Meson / mingw-w64.
In particular, the openblas build needed to be built with the MinGW toolchain that SciPy is also
built with. 

The long-term plan is to work with everyone to get our OpenBLAS / Windows builds updated, and will likely
result in something like the existing system.
