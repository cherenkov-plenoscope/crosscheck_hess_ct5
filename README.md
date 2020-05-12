# Crosscheck with Cherenkov-telescope H.E.S.S. CT5

## Abstract
To crosscheck the tools and algorithms used in the simulation for the Cherenkov-plenoscope, we perform a crosscheck with an existing Cherenkov-telescope. We choose to compare with the 5th telescope named 'CT5' in the [High Energy Stereoscopic System](https://www.mpi-hd.mpg.de/hfm/HESS/) as it is the largest Cherenkov-telescope in 2020. Here we collect CT5's public information to feed our simulations.

![img](readme/hess_overview.jpg)

Image taken from [H.E.S.S. web pages](https://www.mpi-hd.mpg.de/hfm/HESS/pages/about/telescopes/) (2017 July 21). The large telescope in the middle is CT5.

### Periode
I choose the periode of CT5 after its upgrade to a FlashCam image-sensor in mid 2019.
Internal name of this periode:
```
phase2d0 to
phase2d1
```

### Site
Namibia, Khomas Highland, Goellschau.
```
"observation_level_asl_m": 1800,
"earth_magnetic_field_x_muT": 12.5,
"earth_magnetic_field_z_muT": -25.9,
"corsika_atmosphere_id": 10,
"geomagnetic_cutoff_rigidity_GV": 12.5,
```

### Pointing
only near zenith.
```
"azimuth_deg": 0.0,
"zenith_deg": 0.0
```

### Night-sky-background-light
Representative for 1,500h to 2,000h of the darkest observation-time in a year.
Benn and Allison, La Palma.

```
@article{gaug2013night,
    title={Night Sky Background Analysis for the Cherenkov Telescope Array using the Atmoscope instrument},
    author={Gaug, Markus and others},
    journal={arXiv preprint arXiv:1307.3053},
    year={2013}
}
```
Compatible with:
```
@article{preuss2002study,
    title={Study of the photon flux from the night sky at La Palma and Namibia, in the wavelength region relevant for imaging atmospheric Cherenkov telescopes},
    author={Preuss, S and Hermann, G and Hofmann, W and Kohnle, A},
    journal={Nuclear Instruments and Methods in Physics Research Section A: Accelerators, Spectrometers, Detectors and Associated Equipment},
    volume={481},
    number={1},
    pages={229--240},
    year={2002},
    publisher={Elsevier}
}
```
