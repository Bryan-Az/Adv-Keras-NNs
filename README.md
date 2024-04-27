# Adv-Keras-NNs

[Watch the video presentation here!](https://youtu.be/YQX73LEC0z4?si=9TS3hHfp4WPKuk0Z)

This repo tests and modifies the models previously created within my [Tensorflow](https://github.com/Bryan-Az/TF-PyTorch-Jax-NN) & [Keras, HuggingFace, and FastAI](https://github.com/Bryan-Az/Keras-HF-FastAi) repository.

## [Part 1] Regularization A/B and Data Augmentation
In this section, regularizations is A/B tested in the Tabular Model directory.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm, specified differently for each notebook.

> Notebook A Applies:
- Regularizations: BatchNorm in sequential API, L1, Dropout, and Earlystop: Validation Loss

> Notebook B Applies:
- Regularizations: BatchNorm in Keras API, L2, Montecarlo dropout, and Earlystop: Validation Loss

Data augmentation methods is applied in all models (NLP, Tabular, and Vision).

> Data Augmentation applied: KerasCV (images/video), TSAug (time-series/numerical), FastAI (text) on: 
- Custom text model.
- Custom tabular model.
- Custom vision model.

## [Part 2] KerasTuner, Custom Layers, Optimization, Custom Loss/Regularizer, Training, and Evaluation
In this section, the tabular model in part 1 is advanced by adding important model attributes such as normalization, optimization, loss, and activation and Hyperparameter tuning.

> Normalization Layer: BatchNorm

> Custom Layer: Einsum matrix multiplication.

> Optimizer and Initialization applied: Adam Momentum Optimizer

> Custom Loss Metric Applied: HuberLoss.

> Custom Activation Applied: l1 regularizer

> Hyperparameter tuning: KerasTuner.
 # References
- [Tensorflow](tensorflow.org)
- [Tensorflow, Data Augmentation](https://www.tensorflow.org/tutorials/images/data_augmentation)
- [Keras, Data Augmentation](https://keras.io/keras_cv/)
- [Facebook AI, Data Augmentation](https://ai.facebook.com/blog/augly-a-new-data-augmentation-library-to-help-build-more-robust-ai-models/)
- [Fast AI, Data Augmentation](https://github.com/fastai/fastbook/blob/master/07_sizing_and_tta.ipynb)
 - [Bruno Krisinski, Data Augmentation](https://brunokrinski.github.io/awesome-data-augmentation/)
 - [AgaMiko, Data Augmentation](https://github.com/AgaMiko/data-augmentation-review)
 - [Hands-on ML, Neural Networks with Keras](https://github.com/ageron/handson-ml3/blob/main/10_neural_nets_with_keras.ipynb)
 - [Hands-on ML, Keras Tuner](https://github.com/ageron/handson-ml3/blob/main/11_training_deep_neural_networks.ipynb)
 - [Hands-on ML, Training](https://github.com/ageron/handson-ml2/blob/master/11_training_deep_neural_networks.ipynb)
 - [Hands-on ML, Custom Models](https://github.com/ageron/handson-ml2/blob/master/12_custom_models_and_training_with_tensorflow.ipynb)


