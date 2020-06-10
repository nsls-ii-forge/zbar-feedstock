About zbar
==========

Home: http://zbar.sourceforge.net/

Package license: LGPL-2.1

Feedstock license: BSD 3-Clause

Summary: Zbar barcode reader library

ZBar is an open source software suite for reading bar codes from various
sources, such as video streams, image files and raw intensity sensors. It
supports many popular symbologies (types of bar codes) including
EAN-13/UPC-A, UPC-E, EAN-8, Code 128, Code 39, Interleaved 2 of 5 and QR
Code.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=201&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/zbar-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=201&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/zbar-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=201&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/zbar-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-zbar-green.svg)](https://anaconda.org/nsls2forge/zbar) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/zbar.svg)](https://anaconda.org/nsls2forge/zbar) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/zbar.svg)](https://anaconda.org/nsls2forge/zbar) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/zbar.svg)](https://anaconda.org/nsls2forge/zbar) |

Installing zbar
===============

Installing `zbar` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `zbar` can be installed with:

```
conda install zbar
```

It is possible to list all of the versions of `zbar` available on your platform with:

```
conda search zbar --channel nsls2forge
```




Updating zbar-feedstock
=======================

If you would like to improve the zbar recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/zbar-feedstock are
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


