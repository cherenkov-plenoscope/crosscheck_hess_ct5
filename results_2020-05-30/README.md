# 2020 May 30
```starter_kit``` commit ```106dba33```.
The algorithm used to estimate the instrument-response is based on a grid-approach and not a core-position-scatter-approach.

Estimating the instrument-resonse of H.E.S.S. CT5 on trigger-level using the simulation-tools of the Cherenkov-plenoscope.

## Ratescan
<img src="figures/ratescan_namibia.png" width="640">

The rates below a trigger-threshold of ```40 p.e.``` do saturate, and do not grow further because of limited statistics.
The effective areas, and acceptances are for a trigger-threshold of ```60 p.e.```, see vertical line.

## Effective area for gamma-rays
<img src="figures/namibia_gamma_area.png" width="640">

## Effective acceptance (area x solid angle) for cosmic-rays

### Proton

<img src="figures/namibia_proton_acceptance.png" width="640">

### Helium

<img src="figures/namibia_helium_acceptance.png" width="640">

### Electron + Positron

<img src="figures/namibia_electron_acceptance.png" width="640">

## Triggerprobability vs. true Cherenkov-size


| Gamma         | Proton        | Helium  | Electron |
| ------------- | ------------- | ------- | -------- |
| <img src="figures/namibia_gamma_trigger_probability_vs_cherenkov_size.jpg" width="320"> | <img src="figures/namibia_proton_trigger_probability_vs_cherenkov_size.jpg" width="320"> | <img src="figures/namibia_helium_trigger_probability_vs_cherenkov_size.jpg" width="320"> | <img src="figures/namibia_electron_trigger_probability_vs_cherenkov_size.jpg" width="320"> |

## Triggerprobability vs. angle between pointing and primary

| Gamma         | Proton        | Helium  | Electron |
| ------------- | ------------- | ------- | -------- |
| <img src="figures/namibia_gamma_trigger_probability_vs_offaxis.jpg" width="320"> | <img src="figures/namibia_proton_trigger_probability_vs_offaxis.jpg" width="320"> | <img src="figures/namibia_helium_trigger_probability_vs_offaxis.jpg" width="320"> | <img src="figures/namibia_electron_trigger_probability_vs_offaxis.jpg" width="320"> |

## Cherenkov-pool on observation-level

Gamma

| Gamma         | Proton        | Helium  | Electron |
| ------------- | ------------- | ------- | -------- |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000000.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000000.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000000.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000000.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000001.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000001.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000001.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000001.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000002.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000002.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000002.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000002.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000003.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000003.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000003.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000003.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000004.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000004.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000004.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000004.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000005.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000005.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000005.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000005.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000006.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000006.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000006.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000006.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000007.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000007.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000007.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000007.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000008.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000008.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000008.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000008.jpg" width="240"> |
| <img src="figures/namibia_gamma_grid_area_pasttrigger_000009.jpg" width="240"> | <img src="figures/namibia_proton_grid_area_pasttrigger_000009.jpg" width="240"> | <img src="figures/namibia_helium_grid_area_pasttrigger_000009.jpg" width="240"> | <img src="figures/namibia_electron_grid_area_pasttrigger_000009.jpg" width="240"> |

## Flux of airshowers

<img src="figures/airshower_differential_flux.png" width="640">

This is used to integrate the trigger-rates shown in the ratescan.
The flux of airshowers in earth's atmosphere is based on the flux of cosmic-rays outside of earth's atmosphere and the geomagnetic cutoff. Here we assume that the flux of airshowers below a rigidity of ```~10GV``` is reduced down to ```5%```.

```
@article{patrignani201730,
  title={30.1. primary spectra},
  author={Patrignani, C and others},
  journal={URL http://pdg. lbl. gov/2017/reviews/rpp2017-rev-cosmic-rays. pdf}
}

@article{aguilar2015precision,
  title={
      Precision measurement of the proton flux in primary cosmic rays from
      rigidity 1 GV to 1.8 TV with the Alpha Magnetic Spectrometer on the
      International Space Station},
  author={
      Aguilar, M and
      Aisa, D and
      Alpat, B and
      Alvino, A and
      Ambrosi, G and
      Andeen, K and
      Arruda, L and
      Attig, N and
      Azzarello, P and
      Bachlechner, A and
      others},
  journal={Physical Review Letters},
  volume={114},
  number={17},
  pages={171103},
  year={2015},
  publisher={APS}
}

@article{aguilar2014precision,
  title={
    Precision measurement of the (e++ e-) flux in primary cosmic rays
    from 0.5 GeV to 1 TeV with the Alpha Magnetic Spectrometer on the
    International Space Station
  },
  author={
    Aguilar, M and
    Aisa, D and
    Alpat, B and
    Alvino, A and
    Ambrosi, G and
    Andeen, K and
    Arruda, L and
    Attig, N and
    Azzarello, P and
    Bachlechner, A
    and others
  },
  journal={Physical review letters},
  volume={113},
  number={22},
  pages={221102},
  year={2014},
  publisher={APS}
}

```
