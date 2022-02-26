# DLwPyFCholletBook
Repo for all code used while reading Deep Learning with Python by Francois Chollet.

Setting up Tensforflow on Apple Silicon: https://github.com/apple/tensorflow_macos/issues/153

1. Make sure you don't have Anaconda installed. If you do, remove it following instructions here:https://docs.anaconda.com/anaconda/install/uninstall/
2. Install miniforge as follows:
```
brew install miniforge
```
Ref: https://naolin.medium.com/conda-on-m1-mac-with-miniforge-bbc4e3924f2b

```
python3 -m pip install tensorflow-macos
```
3. Add the GPU plugin
```
python -m pip install tensorflow-metal
```
Ref: https://developer.apple.com/metal/tensorflow-plugin/
