# DCGAN 
[Paper](https://arxiv.org/abs/1511.06434)

## model architecture for stable DC GANs 
- [x] Replace any pooling layers with strided convolutions (discriminator) and fractional-strided convolutions (generator).
- [x] Use Batch-norm for generator and discriminator.
- [x] Remove fully connected layers.
- [x] Use Relu activation in generator for all layers except for the output, which uses Tanh.
- [x] Use leakyRelu activation in the discriminator for all layers.
  - [x] alpha = 0.2

## dataset
- [x] mnist
![img](/imgs/dcgan-mnist.mp4)
- [x] fashion mnist
![img](/imgs/dcgan-fashion.mp4)
- [ ] celebA
