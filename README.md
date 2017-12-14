# Weakly Supervised Object Localization 
A no-frills implementation of object localization where data labels only include presence/absence information per image.


## Details
### Dependencies
keras 1.2.2
tensorflow 0.10

### Usage
run files in this Order
```
train.py 
draw_sample_results.py
```
### others
CIFAR10 dataset used for now
InceptionV3 used for convolution stack

## References
* [Is Object Localization free?](http://www.di.ens.fr/~josef/publications/Oquab15.pdf)
* [Learning Deep Features for Discriminative Localization](https://arxiv.org/pdf/1512.04150.pdf)
