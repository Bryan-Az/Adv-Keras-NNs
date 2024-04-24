# Adv-Keras-NNs

This repo tests and modifies the models previously created within my [Tensorflow](https://github.com/Bryan-Az/TF-PyTorch-Jax-NN) repository.

## [Part 1] Regularization and Data Augmentation
In this section, the custom architecture will be A/B tested and modified to compare different regularization techniques and data augmentation methods.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm.

> Data Augmentation compared: KerasCV (images/video), NLPAug (text), FastAI (tabular data).

> Hyperparameter tuning via KerasTuner

The A/B modifications in part 1 are tested using the following Tensorflow models:

- Custom text model.
- Custom tabular model.
- Custom vision model.

## [Part 2] Tensorboard: Normalization, Optimization, Training, and Evaluation
In this section, methods like Tensorboard, normalization layers, optimization techniques, model training, and tuning of the weight initializer, loss activation and evaluation metrics are implemented.

 > Normalizations applied: alpha dropout via custom layer, a custom tensorflow.Dataset in the training loop.

 > Optimizers applied: momentum optimization via custom optimizer & learning rate scheduler, a custom ResNet (Residual Network) model with He Normal initialization.

 > Loss/Eval Metrics Applied: HuberLoss, HuberMetric.

 > Activations Applied: ReLU, Leakly ReLU
