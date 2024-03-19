# Model-Validation: Human-Liver-Microsomal-Stability

This repository contains validation results of the Human Liver Microsomal Stability Model as part of the Week 2 tasks at [Ersilia](https://github.com/ersilia-os/ersilia) for [Outreachy](https://www.outreachy.org/) May 2024 cohort contribution phase. The validation is done in three steps-

- **T1 Model bias** (i.e. models giving very high values or low values): Running predictions for a list of 1000 diverse molecules and plotting the results in a scatter plot.

- **T2 Reproducibility:** Check whether we are able to reproduce the exact values / a figure / that authors obtained when training the model in the first place? This means reading the publication and identifying for example a compound identified using that model and checking that we obtain the same values.

- **T3 Performance:** Check whether we can get the model to give accurate results in external datasets? This is more time consuming and will be done by identifying a public dataset that has not been used in model training, and running predictions to build AUROC curves - to simplify reports, we will only focus on AUROC or R2 as metrics now.


## About the Model

The GitHub repository of the model used for validation can be found [here](https://github.com/ersilia-os/eos31ve). The model integrates liver-mediated drug metabolism to evaluate a compound's stability within the human body. Leveraging a proprietary dataset of 4300 compounds with associated Human Liver Microsomal (HLM) data, particularly in vitro half-life measurements (classified as unstable if ≤ 30 min and stable if > 30 min), the NIH-NCATS group developed a classifier. This classifier utilizes machine learning techniques to predict the stability of compounds based on their chemical properties and interactions with human liver microsomes, aiding in drug development and optimization processes.


## Repository organization

## How to use this repository

## Where to get more help:

- Read Outreachy's contribution [tasks](https://ersilia.gitbook.io/ersilia-book/contributors/internships/outreachy-summer-2024)
- Read Ersilia's [documentation](https://ersilia.gitbook.io/ersilia-book)
- Get inspiration from Ersilia's work, for example on this repository for [data processing](https://github.com/ersilia-os/open-data-cleaning)
- Use Slack to ask the mentors and the other interns for help!

## License
