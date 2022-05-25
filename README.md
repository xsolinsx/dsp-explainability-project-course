# dsp-explainability-project-course

Tests on explainability/interpretability libraries and comparison with classical feature selection algorithms during my Master's Degree in Data Science.

## Installing

Clone this repository.

Cd into it.

Download (a subset of the) datasets from [here](https://osf.io/fv8td/) and unpack everything such that the content of _datasets_ is similar to the following:

``` bash
datasets
│   .gitignore
│
├───GSE2109_Breast
│   │   GSE2109_Breast.txt
│   │   GSE2109_Breast_Clinical.txt
│   │   GSE2109_Breast_Description.md
│   │   Samples.txt
│   │
│   ├───Class
│   │       Histological__Grade.txt
│   │       Histological__Histology.txt
│   │       MolecularMarker__ER.txt
│   │       MolecularMarker__HER2_Neu.txt
│   │       PatientCharacteristic__Family_History_of_Cancer.txt
│   │       PatientCharacteristic__Multiple_Tumors.txt
│   │       Stage__Stage.txt
│   │
│   └───Covariate
│           PatientCharacteristic__Alcohol_Consumption.txt
│           PatientCharacteristic__Ethnic_Background.txt
│           PatientCharacteristic__Family_History_of_Cancer.txt
│           PatientCharacteristic__Oophorectomy.txt
│           PatientCharacteristic__Patient_Age.txt
│           PatientCharacteristic__Tobacco_Use.txt
│...
```

``` bash
pip3 install -r requirements.txt
```

## Usage

Run the notebooks in the correct order.

## Copyright & License

- Copyright (C) 2021 Eric Solinas <<https://github.com/xsolinsx>>
- Licensed under the terms of the [MIT License](LICENSE)
