### Overview
This repo contains my implementation of cnn backbones.
So far, I have implemented the following backbones:
- VGG
- DenseNet

The implementation is done in Pytorch, using PytorchLightning CLI and Tensorboard for logging.

The environment is managed using conda, currently `pytorch-env`

### Todo:
- enhance the data modules to allow control from config file for number of workers etc.
- add torch metrics and calculate classification specific metrics