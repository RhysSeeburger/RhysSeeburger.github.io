---
type: gallery-details
active: true

# Display name
title: Hunting for Dark Companions

url: static/img/kareem_bh_closeup_star_behind.png
brief: Finding the elusive dormant stellar mass black holes in the Milky Way.

keywords:
    - Stellar Astrophysics
    - Spectroscopy
    - Gaia
    - Black Holes
    - Binaries
    - PhD

preview-image: static/img/kareem_bh_closeup_star_behind.png

# Image slideshow
images:
    - url: /static/img/kareem_bh_closeup_star_behind.png
      caption: |
        Our nearest black hole, Gaia BH1. Image Credit: Thomas Müller, HdA/MPIA
    - url: /static/img/ANIMATE_Unicorn_bin1_lam1_q0.18.gif
      caption: |
        An animation of the disentangling process. The top panel shows the observed spectra, the middle panel shows the disentangled spectra, and the bottom panel shows the residuals. The disentangled spectra are shown in red and blue, and the residuals are shown in black.
information: |
    ### Hunting for Dark Companions

    * Finding the elusive dormant stellar mass black holes in the Milky Way.


---

### Hunting for Dark Companions

I am currently working on my PhD Thesis, supervised by Hans-Walter Rix at the Max Planck Institute for Astronomy. According to population models, we expect around 10 billion stellar mass black holes to exist in the Milky Way - however, to this day, detections of these objects are very rare. My work aims to search for stellar mass, dormant black holes in close, detached binaries, using a variety of possible signatures. These include, but are not limited to, ellipsoidal variation and doppler beaning of the light curve of the stellar companion, red- and blueshift variations in the star's spectrum, and light-centroid wobble of the companion’s position on the night sky. To this end, photometric, spectroscopic and astrometric data is used. This will allow us to characterise stellar mass black holes in binaries, or, if none are found, place constraints on their populations.

### Disentangling Composite Spectra

So far, my work has focussed on spectral disentangling based on an approach presented by Simon & Sturm (1994). Unlike most spectral disentangling methods used today, this algorithm does not require the use of templates, instead employing linear algebra and multi-epoch spectra to disentangle the composite spectra into their individual components. This has the advantage of being able to detect uncommon or strange secondary signatures, for which there may be no templates available (such as, for example, stripped sellar cores.) So far, I have implemented and updated this algorithm in python, including methods that allow an almost "blind" analysis of the spectra, without requiring further knowledge of the RVs, mass- and light ratio, and centre-of-mass velocity of the system. The code has been successfully applied to some proposed black hole candidates in El-Badry et. al (2022). Now, I am starting to apply the code to LAMOST multi-epoch spectral data, to identify and characterise binaries.