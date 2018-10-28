About orange3-network
=====================

Home: https://github.com/biolab/orange3-network

Package license: GPL-3.0

Feedstock license: BSD 3-Clause

Summary: Networks add-on for Orange 3 data mining software package.



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/conda-forge/orange3-network-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/orange3-network-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/orange3-network-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/orange3-network-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/conda-forge/orange3-network-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/conda-forge/orange3-network-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-orange3--network-green.svg)](https://anaconda.org/conda-forge/orange3-network) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/orange3-network.svg)](https://anaconda.org/conda-forge/orange3-network) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/orange3-network.svg)](https://anaconda.org/conda-forge/orange3-network) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/orange3-network.svg)](https://anaconda.org/conda-forge/orange3-network) |

Installing orange3-network
==========================

Installing `orange3-network` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `orange3-network` can be installed with:

```
conda install orange3-network
```

It is possible to list all of the versions of `orange3-network` available on your platform with:

```
conda search orange3-network --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating orange3-network-feedstock
==================================

If you would like to improve the orange3-network recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/orange3-network-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
