# Sentinel-5P localized data

## Overview
The [Sentinal-5P](https://sentinel.esa.int/web/sentinel/missions/sentinel-5p) satellite contains a 4 channel spectrometer, named TROPOMI.


 The main characteristics of TROPOMI are:

    Type: passive grating imaging spectrometer
    Configuration: Push broom staring (non-scanning) in nadir viewing
    Swath width: 2,600 km
    Spatial sampling: 7x7 km2
    Spectral: 4 spectrometers, each electronically split in two bands (2 in UV, 2 in VIS, 2 in NIR, 2 in SWIR)
    Radiometric accuracy (absolute): 1.6% (SWIR) to 1.9% (UV) of the measured earth spectral reflectance.
    Overall mass: 204.3 kg not including ICU (16.7 kg) that is integrated on the platform, separated from the instrument.
    Dimensions: 1.40 x 0.65 x 0.75 m
    Design lifetime: 7 years
    Average power consumption: 155 W
    Generated data volume: 139 Gbits per full orbit.

## Instrument description

Source: [Algorithm theoretical basis document for the TROPOMI L01b data processor
issue 10.0.0, 2022-03-31 – released
](https://sentinel.esa.int/documents/247904/2476257/Sentinel-5P-TROPOMI-Level-1B-ATBD)

The TROPOMI instrument (TROPOMI) is a space-borne nadir-viewing hyperspectral imager with four separate
spectrometers covering non-overlapping and non-contiguous wavelength bands between the ultraviolet and the
shortwave infrared. The purpose of TROPOMI is the measurement of atmospheric properties and constituents.
The instrument uses passive remote sensing techniques to attain its objective by measuring at the top of
the atmosphere the solar radiation reflected by and radiated from the Earth. The instrument operates in a
push-broom configuration with a wide swath. Light from the entire swath is recorded simultaneously and
dispersed onto two-dimensional imaging detectors: the position along the swath is projected onto one direction
of the detectors, and the spectral information for each position is projected on the other direction. From the
spectra obtained it is possible to retrieve information on the total column densities and vertical profiles of a
number of atmospheric trace gases like <b>NO2, O3, CH4, CO and SO2</b>. In addition, information relating to clouds,
surface reflectance, and aerosols can be derived. The swath is 108 degrees wide and this, combined with a
polar circular orbit of 817 km altitude, allows TROPOMI to achieve complete daily surface coverage

## Optics Layout
TROPOMI utilizes a single telescope to form an image of the target area onto a rectangular slit that acts as
the entrance slit of the spectrometer system. There are four different spectrometers, each with its own optics
and detector: mediumwave ultraviolet (UV), longwave ultraviolet combined with visible (UVIS), near infrared
(NIR), and shortwave infrared (SWIR). The spectrometers for UV, UVIS and NIR are jointly referred to as
UVN. Radiation for the SWIR spectrometer is transferred by an optical relay part in the UVN system from the
telescope to an interface position (the pupil stop) for the SWIR spectrometer. This is done because of the more
stringent thermal requirements on the SWIR part of the instrument

