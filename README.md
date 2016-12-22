About gorgon-hello
==================

Home: 

Package license: 

Feedstock license: BSD 3-Clause

Summary: Gorgon 'Hello World!'



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/gorgoncryoem/gorgon-hello-feedstock.svg?style=shield)](https://circleci.com/gh/gorgoncryoem/gorgon-hello-feedstock)
OSX: [![TravisCI](https://travis-ci.org/gorgoncryoem/gorgon-hello-feedstock.svg?branch=master)](https://travis-ci.org/gorgoncryoem/gorgon-hello-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/gorgoncryoem/gorgon-hello-feedstock?svg=True)](https://ci.appveyor.com/project/gorgoncryoem/gorgon-hello-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/gorgoncryoem/gorgon-hello/badges/version.svg)](https://anaconda.org/gorgoncryoem/gorgon-hello)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/gorgoncryoem/gorgon-hello/badges/downloads.svg)](https://anaconda.org/gorgoncryoem/gorgon-hello)

Installing gorgon-hello
=======================

Installing `gorgon-hello` from the `gorgoncryoem` channel can be achieved by adding `gorgoncryoem` to your channels with:

```
conda config --add channels gorgoncryoem
```

Once the `gorgoncryoem` channel has been enabled, `gorgon-hello` can be installed with:

```
conda install gorgon-hello
```

It is possible to list all of the versions of `gorgon-hello` available on your platform with:

```
conda search gorgon-hello --channel gorgoncryoem
```




Updating gorgon-hello-feedstock
===============================

If you would like to improve the gorgon-hello recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`gorgoncryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `gorgoncryoem` channel.
Note that all branches in the gorgoncryoem/gorgon-hello-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
