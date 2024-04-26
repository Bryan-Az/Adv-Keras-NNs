# Adv-Keras-NNs

This repo tests and modifies the models previously created within my [Tensorflow](https://github.com/Bryan-Az/TF-PyTorch-Jax-NN) & [Keras, HuggingFace, and FastAI](https://github.com/Bryan-Az/Keras-HF-FastAi) repository.

## [Part 1] Regularization and Data Augmentation
In this section, the custom architecture will be A/B tested and modified to compare different regularization techniques and data augmentation methods.

>  Regularizations compared: L1/L2, Dropout, Earlystop, Montecarlo dropout, Various Initializations, Batch Norm, specified differently for each notebook.

> Data Augmentation: KerasCV (images/video), NLPAug (text), FastAI (tabular data), the same in both notebooks.

> Hyperparameter tuning via KerasTuner in both notebooks.

The A/B modifications in part 1 are tested using the following Tensorflow models:

- Custom text model.
- Custom tabular model.
- Custom vision model.

 To conduct an A/B like experiment, in all directories, there is a Notebook A and Notebook B. 
> Notebook A Applies:
- Regularizations: BatchNorm in Keras API, L1, Dropout, and Earlystop: Validation Loss

> Notebook B Applies:
- Regularizations: BatchNorm in sequential layer, L2, Montecarlo dropout, and Earlystop: Accuracy

## [Part 2] Tensorboard: Normalization, Optimization, Training, and Evaluation
In this section, methods like Tensorboard, normalization layers, optimization techniques, model training, and tuning of the weight initializer, loss activation and evaluation metrics are implemented.

 > Normalizations applied: alpha dropout via custom layer, a custom tensorflow.Dataset in the training loop.

 > Optimizers applied: momentum optimization via custom optimizer & learning rate scheduler, a custom ResNet (Residual Network) model with He Normal initialization.

 > Loss/Eval Metrics Applied: HuberLoss, HuberMetric.

 > Activations Applied: ReLU, Leakly ReLU


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


