# Getting started tensorflow2

This is a repo containing my avance in the course Getting started with tensorflow2 of Coursera


### Setup
Running tensorflow docker container
```bash
docker run --gpus all -it --rm -p 8888:8888 -v $(pwd):/tf/getting-started-tensorflow tensorflow/tensorflow:latest-gpu-jupyter
```