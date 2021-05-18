# Morphological traits of reef corals predict extinction risk but not conservation status

[![](https://img.shields.io/badge/doi-10.17605/OSF.IO/GB5TY-orange.svg)](https://doi.org/10.17605/OSF.IO/GB5TY)
[![](https://img.shields.io/github/languages/code-size/nussaibahrs/iucn2021.svg)](https://github.com/nussaibahrs/iucn2021)

*Nussaïbah B. Raja, Andreas Lauchstedt, John M. Pandolfi, Sun W. Kim,
Ann F. Budd & Wolfgang Kiessling*

This folder contains all required scripts to train and evaluate the modern morphology model (trained using modern data).

* **00-load_data.R:** Loads required data.

* **01-predict_threat.R:** Calculates the extinction risk of modern corals using the FMM model.

* **02-analysis_h20_automl_fossil.R:** Runs the AutoML algorithm using fossil data, saves the generated model and calculates the optimised decision threhold for each of the models. 

* **03-select_best_model.R:** Computes the metrics for model evaluation to select the best MMM model.

## Troubleshooting

The issue tracker is the preferred channel for bug reports. You may also
contact me [by email](mailto:nussaibah.raja.schoob@fau.de).
