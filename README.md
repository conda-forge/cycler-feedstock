Installing cycler
-----------------

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
-----------------

Conda forge is a GitHub organization containing a collection of repositories,
with each repository representing a single conda recipe. A repository such as
this is known as a feedstock.
Each feedstock has continuous integration enabled to automatically build
(where appropriate) on Linux, Windows and OSX thanks to the awesome service provided by
of [CircleCI](https://circleci.com/), [AppVeyor](http://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) respectively.

To manage the continuous integration, and ensure that each of the respective
configurations are consistent across each of the recipe repositories
[conda-smithy](http://github.com/conda-forge/conda-smithy) has a collection of
tools for automatically generating the circle.yml, appveyor.yml and .travis.yml
based on the conda-forge.yml within this repository.


Terminology
-----------

**feedstock** - the conda recipe (raw material)
**conda-smithy** - the tool which helps orchestrate the recipe/feedstock.
                   Its primary use is in the construction of the CI .yml files.
**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating cycler
---------------

Current build status
====================
Linux: [![Circle CI](https://circleci.com/gh/conda-forge/cycler-feedstock.svg?style=svg)](https://circleci.com/gh/conda-forge/cycler-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/cycler-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/cycler-feedstock) 
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/cycler-feedstock?svg=True)](https://ci.appveyor.com/project/pelson/cycler-feedstock/branch/master)


TODO
