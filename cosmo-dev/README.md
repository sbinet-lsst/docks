binet/cosmo-dev
===============

`binet/cosmo-dev` is a container where all the dependencies for `SALT-2` are installed (`cython`, `gfortran`, `numpy`, `BLAS/Lapack` and `JLA`) have been installed.
Eventually, `CosmoMC` will be installed too (needs cmbant/CosmoMC#2).

## Usage

```sh
$ docker run -h dev -i -t binet/cosmo-dev bash

docker> which snfit
/usr/local/bin/snfit

docker> exit
```
