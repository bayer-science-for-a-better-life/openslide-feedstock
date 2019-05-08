About openslide
===============

Home: https://www.openslide.org

Package license: LGPL 2.1

Feedstock license: BSD 3-Clause

Summary: OpenSlide is a C library that provides a simple interface to read whole-slide images (also known as virtual slides).



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/openslide-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/openslide-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>
      <img src="https://img.shields.io/badge/linux-disabled-lightgrey.svg" alt="linux disabled">
    </td>
  </tr>
  <tr>
    <td>OSX</td>
    <td>
      <img src="https://img.shields.io/badge/OSX-disabled-lightgrey.svg" alt="OSX disabled">
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openslide-green.svg)](https://anaconda.org/sdvillal/openslide) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/openslide.svg)](https://anaconda.org/sdvillal/openslide) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/openslide.svg)](https://anaconda.org/sdvillal/openslide) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/openslide.svg)](https://anaconda.org/sdvillal/openslide) |

Installing openslide
====================

Installing `openslide` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
```

Once the `sdvillal` channel has been enabled, `openslide` can be installed with:

```
conda install openslide
```

It is possible to list all of the versions of `openslide` available on your platform with:

```
conda search openslide --channel sdvillal
```




Updating openslide-feedstock
============================

If you would like to improve the openslide recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/openslide-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@sdvillal](https://github.com/sdvillal/)

