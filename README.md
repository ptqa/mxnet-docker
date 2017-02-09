# Overview

This repo contains rockerfiles to build docker images with mxnet with pytho3.6/python2.7.

# Build
Install [rocker](https://github.com/grammarly/rocker/)
## python 2.7
```
rocker build -f Rockerfile.python2.7 --push
```
## python 3.6 (GPU)
```
rocker build -f Rockerfile.python3.6 --push -var type=gpu
```
## python 3.6 (CPU)
```
rocker build -f Rockerfile.python3.6 --push -var type=cpu
```
