# stable-diffusion-playground

## environment

- [macOS 12.5.1](https://www.apple.com/tw/macos/monterey/)
- [Visual Studio Code 1.69.2](https://code.visualstudio.com/)
- [Python 3.10.5](https://www.python.org/)

- [PyTorch Nightly 1.14.0.dev20221007](https://pytorch.org/)
- [Torchvision Nightly 0.15.0.dev20221007](https://pytorch.org/)

- [TensorFlow 2.10.0](https://www.tensorflow.org/?hl=zh-tw)
- [TensorFlow Metal 0.6.0](https://developer.apple.com/metal/tensorflow-plugin/)

# setup

```shell
$ pipenv install jupyterlab
```

# PyTorch setup

- [Run Stable Diffusion on your M1 Mac’s GPU](https://replicate.com/blog/run-stable-diffusion-on-m1-mac)
- [How to use Stable Diffusion in Apple Silicon (M1/M2)](https://huggingface.co/docs/diffusers/main/en/optimization/mps)
- [Waifu Diffusion](https://huggingface.co/hakurei/waifu-diffusion)

```shell
$ brew install cmake protobuf rust

$ pipenv install --pre torch torchvision --index https://download.pytorch.org/whl/nightly/cpu
$ pipenv install transformers==4.19.2 diffusers invisible-watermark
```

# Tensorflow setup

- [TensorFlow with GPU support on Apple Silicon Mac with Homebrew and without Conda / Miniforge](https://medium.com/@sorenlind/tensorflow-with-gpu-support-on-apple-silicon-mac-with-homebrew-and-without-conda-miniforge-915b2f15425b)
- [Stable Diffusion in TensorFlow / Keras](https://github.com/divamgupta/stable-diffusion-tensorflow)

```shell
$ pipenv install tensorflow-macos
$ pipenv install tensorflow-metal
$ pip install git+https://github.com/divamgupta/stable-diffusion-tensorflow
$ pipenv install tensorflow-addons
$ pipenv install ftfy
```
