<!--
  The pictures of this page are drawn in Vanilla-Sphere/sphere-blink (scripts/build_readme_art.py, docs/readme/)
  and named here by the commit that holds them, through the jsDelivr mirror of GitHub
  (cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@<commit>/...), so that GitHub serves them from its own image
  cache. A path into raw.githubusercontent.com answered "503" in parts of Asia on 2026-11-15.
  To change a picture: commit it in sphere-blink, then replace the commit id everywhere in this file.
-->

<div align="center">

<a href="https://vanillasphere.com"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/banner.svg" alt="Vanilla Sphere" width="100%"></a>

### Explore the sky. Connect the observations. Discover what moves.

**An independent team at the NASA Space Apps Challenge 2026**<br>
Challenge: [Planet X and SPHEREx](https://www.spaceappschallenge.org/2026/challenges/planet-x-and-spherex/?tab=details)

<img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/award.svg" alt="Second prize at the Hà Nội local event of the 2026 NASA Space Apps Challenge, challenge Planet X and SPHEREx" height="72">

<a href="https://vanillasphere.com"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-live.svg" alt="Open the live site" height="38"></a>
<a href="https://github.com/Vanilla-Sphere/sphere-blink"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-source.svg" alt="Source code" height="38"></a>
<a href="https://github.com/Vanilla-Sphere/sphere-blink/blob/main/docs/README.md"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-docs.svg" alt="Documentation" height="38"></a>
<a href="https://github.com/Vanilla-Sphere/sphere-blink/blob/main/docs/science/README.md"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-science.svg" alt="Science and algorithms" height="38"></a>
<a href="https://vanillasphere.com/docs"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-api.svg" alt="API explorer" height="38"></a>

[![Challenge](https://img.shields.io/badge/NASA%20Space%20Apps-2026-0b3d91?style=flat-square&logo=nasa&logoColor=white)](https://www.spaceappschallenge.org/2026/)
[![Research](https://img.shields.io/badge/SPHEREx-Level%202-b58afb?style=flat-square)](https://irsa.ipac.caltech.edu/)
[![Live site](https://img.shields.io/badge/live-vanillasphere.com-b58afb?style=flat-square)](https://vanillasphere.com)
[![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-e9b452?style=flat-square)](https://github.com/Vanilla-Sphere/sphere-blink/blob/main/LICENSE)
[![Tests](https://img.shields.io/github/actions/workflow/status/Vanilla-Sphere/sphere-blink/checks.yml?branch=main&label=tests&style=flat-square)](https://github.com/Vanilla-Sphere/sphere-blink/actions/workflows/checks.yml)
[![Stars](https://img.shields.io/github/stars/Vanilla-Sphere/sphere-blink?style=flat-square&logo=github&label=stars&color=e9b452)](https://github.com/Vanilla-Sphere/sphere-blink/stargazers)
[![Film on YouTube](https://img.shields.io/badge/film-ff0033?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=Nhfgcw2geB4)

</div>

## Who we are

**Vanilla Sphere** is a collaborative astronomy and software engineering team exploring how NASA's **SPHEREx** infrared observations can support the detection, tracking, and identification of celestial objects.

Our work combines scientific data processing, astrometry, motion estimation, cross-matching, and reproducible research.

> [!NOTE]
> We are an **independent hackathon team** and are **not affiliated with or endorsed by NASA, Caltech/IPAC, or ESA**.

## What we built

**[Vanilla Sphere](https://vanillasphere.com)** turns the SPHEREx archive into something anyone can explore: click a point of the sky map, or type coordinates or a name, and the browser plays every SPHEREx image of that patch in time order, with a spectrum, measured motion and a blind search for things that move. Nothing is downloaded in advance, and no AI model runs inside the product.

<div align="center">

<a href="https://vanillasphere.com"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/sky-map.webp" alt="The start screen of Vanilla Sphere: a map of the whole sky; click anywhere to open that patch in SPHEREx data" width="100%"></a>

<img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/pillars.svg" alt="Explore the sky: any position, every SPHEREx image, played as a movie in seconds. Connect the observations: positions, tracks, spectra and brightness over time, for any object. Discover what moves: a blind search, each find checked against NASA/JPL predictions." width="100%">

<a href="https://github.com/Vanilla-Sphere/sphere-blink#what-it-found"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/numbers.svg" alt="102 colours from 0.75 to 5.0 µm. 3I/ATLAS found by a blind search at 99 arcsec per hour. Pluto at 279 sigma by shift-and-stack. About 10 s to a new view, under 1 s the next time. 0 tracks by chance in shuffled searches." width="100%"></a>

</div>

What it found, and what each result was checked against, is in the [README of sphere-blink](https://github.com/Vanilla-Sphere/sphere-blink#what-it-found).

## Watch the film

<div align="center">

<a href="https://www.youtube.com/watch?v=Nhfgcw2geB4"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/film-poster.webp" alt="Watch the film on YouTube. This frame: it caught 3I/ATLAS, one real SPHEREx exposure with the comet in the crosshair" width="100%"></a>

<a href="https://www.youtube.com/watch?v=Nhfgcw2geB4"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/btn-film.svg" alt="Watch the film" height="44"></a>

<sub>The whole product in 83 seconds, on <a href="https://www.youtube.com/@VanillaSphere">our YouTube channel</a>.</sub>

</div>

## Jump straight in

Each button opens a real view on the live site.

<div align="center">

<a href="https://vanillasphere.com/?ra=248.34&amp;dec=-16.98&amp;levels=3&amp;mover=VS-60894-B5F6&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-3i-atlas.svg" alt="3I/ATLAS, interstellar comet" height="38"></a>
<a href="https://vanillasphere.com/?ra=304.14&amp;dec=-23.58&amp;levels=3&amp;mover=VS-60951-4LN9&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-pluto.svg" alt="Pluto, found by stacking" height="38"></a>
<a href="https://vanillasphere.com/?ra=200.70&amp;dec=21.06&amp;levels=3&amp;mover=VS-61191-X387&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-makemake.svg" alt="Makemake, dwarf planet" height="38"></a>
<a href="https://vanillasphere.com/?target=barnard"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-barnard.svg" alt="Barnard's Star, fastest star in the sky" height="38"></a>
<a href="https://vanillasphere.com/?target=eps-indi-b&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-eps-indi-b.svg" alt="Epsilon Indi B, brown dwarf spectrum" height="38"></a>
<a href="https://vanillasphere.com/?target=r-dra&amp;plot=lc&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-r-dra.svg" alt="R Draconis, a star that faded" height="38"></a>
<a href="https://vanillasphere.com/?ra=232.1947&amp;dec=36.631&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-quasar.svg" alt="SDSS J1528+3637, quasar redshift" height="38"></a>
<a href="https://vanillasphere.com/?target=wise-0855&amp;ui=adv"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/go-wise-0855.svg" alt="WISE 0855, coldest brown dwarf" height="38"></a>

</div>

## Our challenge

Astronomical observations of the same sky region are not identical across time. Some objects appear nearly fixed, nearby stars show small proper motions, while Solar System bodies can move significantly between exposures.

We aim to build a transparent workflow that can:

1. **Read and validate SPHEREx Level 2 FITS products**, including image, uncertainty, quality flags, PSF, time and wavelength information.
2. **Translate pixel positions to celestial coordinates** using WCS and uncertainty-aware astrometry.
3. **Associate detections across observations** despite changes in detector geometry, wavelength, noise, and cadence.
4. **Distinguish stationary, slowly moving, and rapidly moving objects** through quantitative motion models.
5. **Identify known sources** using star catalogs and Solar System ephemerides, and highlight candidates that need further verification.

> **Research principle:** A non-detection of motion is not proof of zero motion. We report measurement uncertainty, limitations, and reproducible evidence.

## Repositories

<a href="https://github.com/Vanilla-Sphere/sphere-blink"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/card-sphere-blink.svg" alt="sphere-blink, the product: the engine and the viewer. Python and JavaScript, AGPL-3.0." width="49%"></a>
<a href="https://github.com/Vanilla-Sphere/sphere-blink-ui-tests"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/docs/readme/card-ui-tests.svg" alt="sphere-blink-ui-tests: Playwright tests of the viewer on a desktop and a phone. TypeScript." width="49%"></a>

The whole product is open source, with its full history since the first commit of the hackathon (2026-11-14).

---

<div align="center">

<a href="https://vanillasphere.com"><img src="https://cdn.jsdelivr.net/gh/Vanilla-Sphere/sphere-blink@d4e0bfac1f985763e038d6e54f945aed8bc70d58/web/logo-mark.svg" alt="" width="56"></a>

**Vanilla-Sphere · NASA Space Apps Challenge 2026**

*Scientific curiosity, responsible collaboration, and evidence-first discovery.*

<sub>[YouTube](https://www.youtube.com/@VanillaSphere) · [Brand guidelines](https://github.com/Vanilla-Sphere/.github/blob/main/brand/BRAND.md) · [Brand assets](https://github.com/Vanilla-Sphere/.github/tree/main/brand)</sub>

</div>
