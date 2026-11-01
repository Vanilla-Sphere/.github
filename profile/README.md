<div align="center">

# Vanilla Sphere

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

---

<div align="center">

**Vanilla-Sphere · NASA Space Apps Challenge 2026**

*Scientific curiosity, responsible collaboration, and evidence-first discovery.*

</div>
