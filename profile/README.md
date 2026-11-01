<div align="center">

# 🌌 Vanilla-Sphere

### Explore the sky. Connect the observations. Discover what moves.

**An independent student/team initiative for NASA Space Apps Challenge 2026**  
**Challenge focus: [Planet X and SPHEREx](https://www.spaceappschallenge.org/2026/challenges/planet-x-and-spherex/?tab=details)**

[![Challenge](https://img.shields.io/badge/NASA%20Space%20Apps-2026-15345a)](https://www.spaceappschallenge.org/2026/)
[![Research](https://img.shields.io/badge/SPHEREx-Level%202-147d87)](https://irsa.ipac.caltech.edu/)
[![License](https://img.shields.io/badge/License-Apache--2.0-blue)](https://github.com/Vanilla-Sphere/spherex-research/blob/main/LICENSE)

</div>

## Who we are

**Vanilla-Sphere** is a collaborative astronomy and software engineering team exploring how NASA's **SPHEREx** infrared observations can support the detection, tracking, and identification of celestial objects.

Our work combines scientific data processing, astrometry, motion estimation, cross-matching, and reproducible research. We are an **independent hackathon team** and are **not affiliated with or endorsed by NASA, Caltech/IPAC, or ESA**.

## Our challenge

Astronomical observations of the same sky region are not identical across time. Some objects appear nearly fixed, nearby stars show small proper motions, while Solar System bodies can move significantly between exposures.

We aim to build a transparent workflow that can:

1. **Read and validate SPHEREx Level 2 FITS products**, including image, uncertainty, quality flags, PSF, time and wavelength information.
2. **Translate pixel positions to celestial coordinates** using WCS and uncertainty-aware astrometry.
3. **Associate detections across observations** despite changes in detector geometry, wavelength, noise, and cadence.
4. **Distinguish stationary, slowly moving, and rapidly moving objects** through quantitative motion models.
5. **Identify known sources** using star catalogs and Solar System ephemerides, and highlight candidates that need further verification.

> **Research principle:** A non-detection of motion is not proof of zero motion. We report measurement uncertainty, limitations, and reproducible evidence.

## Projects

| Repository | Purpose |
|---|---|
| **[spherex-research](https://github.com/Vanilla-Sphere/spherex-research)** | Vietnamese technical research report; editable LaTeX source, TikZ figures, FITS/WCS notes, motion-detection algorithms, attribution and automated PDF build |
| **[Organization profile](https://github.com/Vanilla-Sphere/.github)** | Organization overview and shared collaboration information |

### SPHEREx research report

The report covers L0–L4 processing levels, Quick Releases, L2 cutout formats and metadata, spatial WCS, object motion modeling, catalog association, and strategies for tracking moving sources.

- 📄 [Report source and documentation](https://github.com/Vanilla-Sphere/spherex-research)
- 📦 [Releases](https://github.com/Vanilla-Sphere/spherex-research/releases)
- ⚙️ [PDF build workflow](https://github.com/Vanilla-Sphere/spherex-research/actions)

The PDF release link is available once the LaTeX build workflow has completed successfully. **Do not treat a proposed model or an unverified candidate as a confirmed discovery.**

## Technical direction

```text
SPHEREx L2 FITS
    │
    ├── IMAGE / VARIANCE / FLAGS / PSF / WCS / timestamps
    ▼
Quality control + source extraction
    ▼
Astrometry and time-tagged detections
    ├── Stationary and slow-motion modeling ──► Gaia / SIMBAD / 2MASS
    └── Moving-object association ───────────► MPC / JPL Horizons / MOST
    ▼
Candidate evaluation, provenance, and reproducible results
```

**Working areas:** Python, Astropy, FITS, WCS, time-domain astronomy, PSF fitting, source association, ephemerides, LaTeX, and GitHub Actions.

## Team, attribution, and governance

The project was **initiated by [@Duy247](https://github.com/Duy247)**, who established the initial research scope and team project direction. Team members are credited for their actual work in each repository's `CONTRIBUTORS.md`, with supporting commits and pull requests.

We encourage collaborative, documented contributions:

- Use pull requests and peer review for substantive changes.
- Preserve authorship, citations, scientific provenance, and version history.
- Apply the license and `NOTICE` requirements of each repository.
- Keep reproducible build instructions and disclose the limitations of results.

**Open source does not negate attribution.** License terms and repository governance complement each other, but a watermark by itself is not a technical access control.

## Scientific references

- [NASA SPHEREx](https://science.nasa.gov/mission/spherex/)
- [SPHEREx data at IRSA](https://irsa.ipac.caltech.edu/)
- [SPHEREx Archive Documentation](https://caltech-ipac.github.io/spherex-archive-documentation/)
- [Gaia Data Release 3](https://www.cosmos.esa.int/web/gaia/dr3)
- [JPL Horizons](https://ssd.jpl.nasa.gov/horizons/)
- [Minor Planet Center](https://minorplanetcenter.net/)

---

<div align="center">

**Vanilla-Sphere · NASA Space Apps Challenge 2026**

*Scientific curiosity, responsible collaboration, and evidence-first discovery.*

</div>
