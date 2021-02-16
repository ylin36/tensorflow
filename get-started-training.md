## This guide runs off docker desktop on WLS2. w/ nvidia gpu.
### follow instructures here 
https://docs.nvidia.com/cuda/wsl-user-guide/index.html#installing-nvidia-drivers

### Run off docker

```
docker run -it --gpus all -p 8888:8888 tensorflow/tensorflow:latest-gpu-py3-jupyter
```