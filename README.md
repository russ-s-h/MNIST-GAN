# MNIST-GAN
A simple GAN that produces the 10 MNIST digits. Inspired by the model detailed in this [paper](https://arxiv.org/abs/1511.06434) with the accompanying [code](https://github.com/yihui-he/GAN-MNIST) but hopefully this is much easier to understand + read.

## Output
### Tensorflow output after 20 epochs
<img width="938" alt="Tensorflow output after 20 epochs" src="https://user-images.githubusercontent.com/16087998/128794719-9d45121b-0214-4ea5-89b3-81bf6622d56c.png">

### Pytorch output after 20 epochs
<img width="346" alt="Pytorch output after 20 epochs" src="https://user-images.githubusercontent.com/16087998/128794795-e0ec7baa-5252-41f4-9ed6-d00565c6f658.png">

## *Note
Training either model takes hours using just the CPU (both the pytorch and tensorflow models). CUDA accelerates the training process dramatically.
