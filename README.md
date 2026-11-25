# Enzyme Forran OpenMPI packages

This repository builds OpenMPI with clang and flang and packs them into `*.deb` packages.

To run correctly Enzyme requires OpenMPI compiled with flang. We don't have a standard package
that provides it so we build our own. 

The intention is that the `deb` files can be used to install flang/clang compiled OpenMPI in test runners and avoid redundant compilation when running Fortran tests.
