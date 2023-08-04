# Getting started tensorflow2

Run docker container tensorflow
```bash
docker run --gpus all -it --rm -p 8888:8888 -v $(pwd):/tf/getting-started-tensorflow tensorflow/tensorflow:latest-gpu-jupyter
```