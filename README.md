# BNU-beamer

## Overview

This is a beamer template modified based on Metropolis theme. As the developer of the original Metropolis theme wrote, and I quote here

>   Metropolis is a simple, modern Beamer theme suitable for anyone to use. It tries
>   to minimize noise and maximize space for content; the only visual flourish it
>   offers is an (optional) progress bar added to each slide. The core design
>   principles of the theme were described in a blog post
>   [here](http://bloerg.net/2014/09/20/a-modern-beamer-theme.html).

The modifications include: 

-   Primary theme color changed to BNU-Blue (师大蓝)
-   Logo with high-resolution imported. Many thanks to [LeyuDame](https://github.com/LeyuDame) for open-sourcing the high-res logo and corresponding Tikz code
-   Frequently used packages added to the `beamerthememetropolis.sty` file (based on personal preferences)

For a minimal example, please refer to `eng-test.tex` , `chn-test.tex`and their corresponding `.pdf` files. Previews are shown below. 

![English-preview](figs/eng-preview.png)

![Chinese-preview](figs/chn-preview.png)

Compilation of the English version has been tested both on WSL 2 (Ubuntu 22.04.4 LTS) and Windows 11 with TexLive 2022. The Chinese version only passed the test on Windows platform with XeLaTeX (with ctex's  `fontset` specified to `windows`), as support for Chinese fonts on Linux platform is usually terrible. However, LaTeX suffers from bad performance on Windows platform. Maybe will test macOS later? 

For any question, please feel free to contact me via Issues and [email](mailto:202011081001@mail.bnu.edu.cn).