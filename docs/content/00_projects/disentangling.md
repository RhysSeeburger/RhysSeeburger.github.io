---
type: gallery-details
active: true

# Display name
title: Spectral Disentangling

url: static/img/ANIMATE_Unicorn_bin1_lam1_q0.18.gif
brief: Identifying the components of binary stellar spectra

keywords:
    - Stellar Astrophysics
    - Spectroscopy
    - Binaries
    - PhD

preview-image: static/img/ANIMATE_Unicorn_bin1_lam1_q0.18.gif

# Image slideshow
images:
    - url: /static/img/ANIMATE_Unicorn_bin1_lam1_q0.18.gif
      caption: |
        An animation of the disentangling process. The top panel shows the observed spectra, the middle panel shows the disentangled spectra, and the bottom panel shows the residuals. The disentangled spectra are shown in red and blue, and the residuals are shown in black.
information: |

    ### Disentangling Composite Spectra

    So far, my work has focussed on spectral disentangling based on an approach presented by Simon & Sturm (1994). Unlike most spectral disentangling methods used today, this algorithm does not require the use of templates, instead employing linear algebra and multi-epoch spectra to disentangle the composite spectra into their individual components. This has the advantage of being able to detect uncommon or strange secondary signatures, for which there may be no templates available (such as, for example, stripped sellar cores.) So far, I have implemented and updated this algorithm in python, including methods that allow an almost "blind" analysis of the spectra, without requiring further knowledge of the RVs, mass- and light ratio, and centre-of-mass velocity of the system. The code has been successfully applied to some proposed black hole candidates in El-Badry et. al (2022).

---
