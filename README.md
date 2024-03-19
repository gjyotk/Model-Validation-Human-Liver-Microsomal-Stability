# Model-Validation: Human-Liver-Microsomal-Stability

This repository contains validation results of the Human Liver Microsomal Stability Model. The validation is done in three steps-

- T1 Model bias (i.e. models giving very high values or low values): Running predictions for a list of 1000 diverse molecules and plotting the results in a scatter plot.

- T2 Reproducibility: Check whether we are able to reproduce the exact values / a figure / that authors obtained when training the model in the first place? This means reading the publication and identifying for example a compound identified using that model and checking that we obtain the same values.

- T3 Performance: Check whether we can get the model to give accurate results in external datasets? This is more time consuming and will be done by identifying a public dataset that has not been used in model training, and running predictions to build AUROC curves - to simplify reports, we will only focus on AUROC or R2 as metrics now.


## About the Model

The github repo of the model used for validation can be found [here](https://github.com/ersilia-os/eos31ve). The model takes into account the liver-mediated drug metabolism to assess the stability of a compound in the human body. The NIH-NCATS group took a proprietary dataset of 4300 compounds with its associated HLM (in vitro half-life; unstable ≤  30 min, stable >30 min) and used it to train a classifier.


## Repository organization

## How to use this repository

## Where to get more help:

- Read Outreachy's contribution tasks
- Read Ersilia's documentation
- Get inspiration from Ersilia's work, for example on this repository for data processing
- Use Slack to ask the mentors and the other interns for help!

## License
