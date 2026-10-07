# Multi Tour Guide: multilingual GPS tour-guide engine

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23205256.svg)](https://doi.org/10.5281/zenodo.23205256)

*Motore multilingue per guide turistiche GPS*

**Android** · 2020–2021 · version 1.0 (2)  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Multi Tour Guide generalises the folklore tour guide into a reusable engine. The user chooses one of four languages (Slovene dialect, Italian, English, German) with flag buttons; every text of the tour is stored in the four languages. It adds a dedicated map screen, home and back navigation and pinch zoom on images, and was later reused for the carnival-traditions guide.

I designed and programmed this application in 2020–2021. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Language selection with flag buttons; all screens and monologues follow the chosen language.
- Map of the tour sites (`MapsScreen`) and location screen with distances (`LocationScreen`).
- Navigation to the selected site (`Navigate`) and photo gallery (`GalleryScreen`).
- Pinch-to-zoom on images through the ScaleDetector extension.

## Data

Coordinates and multilingual texts are embedded in the app.

## Technology

MIT App Inventor 2: Map, Marker, LocationSensor, ActivityStarter, Camera, Canvas, ImageSprite, ListView, File, TextToSpeech, TinyDB; extension ScaleDetector (MIT).

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## Related repositories

- [folklore-gps-tour-guide-android](https://github.com/massimosbarbaro/folklore-gps-tour-guide-android)
- [carnival-traditions-tour-guide-android](https://github.com/massimosbarbaro/carnival-traditions-tour-guide-android)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). The release is archived on Zenodo with the DOI [10.5281/zenodo.23205256](https://doi.org/10.5281/zenodo.23205256).

> Sbarbaro, Massimo. 2021. *Multi Tour Guide: multilingual GPS tour-guide engine*. Software (Android, 2020–2021), version 1.0 (2). Zenodo. https://doi.org/10.5281/zenodo.23205256.

## License

Released under the [MIT License](LICENSE). © 2020 Massimo Sbarbaro.
