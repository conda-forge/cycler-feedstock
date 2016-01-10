Installing cycler
=================

Installing cycler from the conda-forge channel can be achieved by adding conda-forge to your channels with:

```
conda config --add channels conda-forge
```

Once the conda-forge channel has been enabled, cycler can be installed with:

```
conda install cycler
```

It is possible to list all of the versions of cycler available on your platform with:

```
conda search cycler --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository 
for each of the installable packages. Such a repository is known as a feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](http://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](http://docs.anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and ensure that each of the respective
configurations are consistent across each of the recipe repositories
[conda-smithy](http://github.com/conda-forge/conda-smithy) has a collection of
tools for automatically generating the circle.yml, appveyor.yml and .travis.yml
based on the conda-forge.yml within this repository.


Terminology
===========

**feedstock** - the conda recipe (raw material)
**conda-smithy** - the tool which helps orchestrate the recipe/feedstock.
                   Its primary use is in the construction of the CI .yml files.
**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating cycler
===============

Current build status
--------------------
Linux: [![Circle CI](https://circleci.com/gh/conda-forge/cycler-feedstock.svg?style=svg)](https://circleci.com/gh/conda-forge/cycler-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/cycler-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/cycler-feedstock) 
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/cycler-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/cycler-feedstock/branch/master)


TODO
