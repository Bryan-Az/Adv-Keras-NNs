# [Part 1] Regularization and Data Augmentation
In this section, the custom architecture will be A/B tested and modified to compare different regularization techniques and data augmentation methods.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm.

> Data Augmentation compared: KerasCV (images/video), NLPAug (text), FastAI (tabular data).

> Hyperparameter tuning via KerasTuner

The A/B modifications in part 1 are tested using the following Tensorflow models:

- Custom text model.
- Custom tabular model.
- Custom vision model.

 In all directories, there is a Notebook A and Notebook B. 
> Notebook A Applies:
- Regularizations: BatchNorm in Keras API, L1, Dropout, and Earlystop: Validation Loss


> Data Augmentation:
- For Text
- For Tabular
- For Vision 

> Notebook B Applies:
- Regularizations: BatchNorm in sequential layer, L2, Montecarlo dropout, and Earlystop: Accuracy

> Data Augmentation:
- For Text
- For Tabular
- For Vision 


> Only one notebook will apply HyperParameter tuning.