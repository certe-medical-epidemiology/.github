
<div style="position: relative; height: 410px;">
  <a href="https://github.com/certe-medical-epidemiology/certedata/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certedata/logo.svg" alt="The certedata R package" style="position: absolute; left: 0px; top: 0px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certestyle/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certestyle/logo.svg" alt="The certestyle R package" style="position: absolute; left: 135px; top: 0px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certetoolbox/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certetoolbox/logo.svg" alt="The certetoolbox R package" style="position: absolute; left: 270px; top: 0px; width: 136px; height: 156px;">
  </a>
  
  <a href="https://github.com/certe-medical-epidemiology/certeplot2/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certeplot2/logo.svg" alt="The certeplot2 R package" style="position: absolute; left: 67.5px; top: 122px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certedb/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certedb/logo.svg" alt="The certedb R package" style="position: absolute; left: 202.5px; top: 122px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certeprojects/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certeprojects/logo.svg" alt="The certeprojects R package" style="position: absolute; left: 337.5px; top: 122px; width: 136px; height: 156px;">
  </a>

  <a href="https://github.com/certe-medical-epidemiology/certemail/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certemail/logo.svg" alt="The certemail R package" style="position: absolute; left: 0px; top: 244px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certestats/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certestats/logo.svg" alt="The certestats R package" style="position: absolute; left: 135px; top: 244px; width: 136px; height: 156px;">
  </a>
  <a href="https://github.com/certe-medical-epidemiology/certegis/" target="_blank">
    <img src="https://certe-medical-epidemiology.github.io/certegis/logo.svg" alt="The certegis R package" style="position: absolute; left: 270px; top: 244px; width: 136px; height: 156px;">
  </a>
</div>

These are R packages developed by [**Certe**](https://www.certe.nl), a non-profit medical laboratory in the Northern Netherlands that provides routine diagnostic tests for clinical chemistry and clinical microbiology, as well as medical logistics and a thrombosis service. Their department of Medical Epidemiology, which developed these R packages, conducts (and develops new methods for) medical data analyses, for both routine workflows and scientific research.

Our R packages are not on CRAN since their use is primarily intended for own staff, but they are publicly available to support open science. All our R packages are free to use and licensed under the [GNU General Public License v2.0 (GPL-2)](https://github.com/certe-medical-epidemiology/.github/blob/main/LICENSE.md).

### Install

All our R packages are published [here at R-universe](https://certe-medical-epidemiology.r-universe.dev), allowing anyone to install and update the packages using common methods, such as the RStudio menu bar or `install.packages()`. To add the Certe Medical Epidemiology R-universe to your existing repositories, run:

```r
options(repos = c(
  CerteMedEpi = "https://certe-medical-epidemiology.r-universe.dev",
  options()$repos)
```

You can now install any Certe R package, e.g.:

```r
# our 'loader package' certedata installs all Certe R packages this way:
install.packages("certedata", dependencies = TRUE)

# or install a specific package:
install.packages("certegis")
install.packages("certeplot2")
install.packages("certestats")
```
