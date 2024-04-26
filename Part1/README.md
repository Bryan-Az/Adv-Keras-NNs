# [Part 1] Regularization and Data Augmentation
In this section, the custom architecture will be A/B tested and modified to compare different regularization techniques and data augmentation methods.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm, specified differently for each notebook.

> Data Augmentation compared: KerasCV (images/video), NLPAug (text), FastAI (tabular data), the same in both notebooks.

> Hyperparameter tuning via KerasTuner in both notebooks.

The A/B modifications in part 1 are tested using the following Tensorflow models:

- Custom text model.
- Custom tabular model.
- Custom vision model.

 To conduct an A/B like experiment, in all directories, there is a Notebook A and Notebook B. 
> Notebook A Applies:
- Regularizations: BatchNorm in sequential API, L1, Dropout, and Earlystop: Validation Loss

> Notebook B Applies:
- Regularizations: BatchNorm in Keras API, L2, Montecarlo dropout, and Earlystop: Accuracy