# stable-diffusion-playground

## environment

- [macOS 12.5.1](https://www.apple.com/tw/macos/monterey/)
- [Visual Studio Code 1.69.2](https://code.visualstudio.com/)
- [Python 3.10.5](https://www.python.org/)
- [PyTorch Nightly 1.14.0.dev20221007](https://pytorch.org/)
- [Torchvision Nightly 0.15.0.dev20221007](https://pytorch.org/)

# setup

- [Run Stable Diffusion on your M1 Mac’s GPU](https://replicate.com/blog/run-stable-diffusion-on-m1-mac)
- [How to use Stable Diffusion in Apple Silicon (M1/M2)](https://huggingface.co/docs/diffusers/main/en/optimization/mps)

```
brew install cmake protobuf rust

pipenv install jupyterlab
pipenv install --pre torch torchvision --index https://download.pytorch.org/whl/nightly/cpu
pipenv install transformers==4.19.2 diffusers invisible-watermark
```
