# [Part 1] Regularization A/B and Data Augmentation
In this section, regularizations and tuning techniques will be A/B tested in the Tabular Model directory.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm, specified differently for each notebook.

> Notebook A Applies:
- Regularizations: BatchNorm in sequential API, L1, Dropout, and Earlystop: Validation Loss
- Tuning: KerasTuner

> Notebook B Applies:
- Regularizations: BatchNorm in Keras API, L2, Montecarlo dropout, and Earlystop: Accuracy
- Tuning: KerasTuner

Data augmentation methods will be applied in all models (NLP, Tabular, and Vision).

> Data Augmentation applied: KerasCV (images/video), TSAug (time-series/numerical), FastAI (text) on: 
- Custom text model.
- Custom tabular model.
- Custom vision model.
