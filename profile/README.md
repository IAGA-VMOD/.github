# IAGA V-MOD

This is the home of the working group for geomagnetic field modelling (WG V-MOD) for the [International Association of Geomagnetism and Aeronomy (IAGA)](https://iaga-aiga.org/about/). The main responsibility of V-MOD is the creation of the International Geomagnetic Reference Field (IGRF).

See also:
- https://www.ncei.noaa.gov/services/world-data-system/v-mod-working-group

## IGRF

See also:
- https://www.ncei.noaa.gov/products/international-geomagnetic-reference-field

## IGRF-14

The 14th IGRF is due to be released on 15th November 2024. Candidate models have been submitted for assessment at https://github.com/IAGA-VMOD/IGRF14eval

```mermaid
timeline
    title IGRF-14 Timeline

    section Initiation
    Q1-Q2 2024:
    (End January)<br>Send call to ask for evaluation panel:
    (Mid February)<br>Draft call for candidate models with evaluation panel approval:
    (Early March)<br>Send out call for candidate models/teams:
    (Mid-May)<br>Reminder email to inform task force of teams and candidates

    section Candidate submissions
    Q3 2024:
    (1 June)<br>Each team provides initial details of the number of candidates intended to be submitted:
    (1 October)<br>Submission of final candidate models and description of product and methodology

    section Evaluation
    November 2024:
    (1 November)<br>Evaluation taskforce to provide feedback and suggestions for combination of candidates:
    (15 November)<br>Decide final IGRF models (DGRF-2020, IGRF-2025, SV-2025)

    section Release
    22 November 2024: Issue final models: Create Zenodo record: Update softwares: Update websites

    section Publications
    2025:
    (1 July 2025)<br>Deadline for submission of papers to EPS special issue:
    (1 November 2025)<br>Expected publication date of the IGRF-14 EPS special issue
```

### Release process

1. The final coefficients will be determined and stored in https://github.com/IAGA-VMOD/IGRF14eval
2. The coefficients will be provided in standard formats (`.txt, .dat, .cof, .shc`) and published as a Zenodo archive with `doi:10.5281/zenodo.14012302` [(link to record)](https://doi.org/10.5281/zenodo.14012302)
3. ["Official" IGRF page](https://www.ncei.noaa.gov/products/international-geomagnetic-reference-field) will be updated accordingly
4. Update software:
  - NOAA update `Geomag 7.0`
  - BGS update Fortran code
  - TBD Python packages
  - ...
5. Update online calculators:
  - [NCEI](https://www.ngdc.noaa.gov/geomag/calculators/magcalc.shtml?useFullSite=true)
  - [BGS](https://geomag.bgs.ac.uk/data_service/models_compass/igrf_calc.html)
  - [CCMC](https://ccmc.gsfc.nasa.gov/models/IGRF~13/)
  - ...
6. Notify communities via mailing lists
