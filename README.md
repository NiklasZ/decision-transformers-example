# Decision Transformers Example

The following repository is a demonstration of how to train a [decision transformer](https://arxiv.org/pdf/2106.01345.pdf) 
for the [2D Walker Environment](https://mgoulao.github.io/gym-docs/environments/mujoco/walker2d/).

<div align="center">
  
  ![video/2d_walk.gif](video/2d_walk.gif)

</div>

## Installation
1. Install Python 3.9.
2. Install `requirements.txt` (e.g via `pip install -r requirements.txt`).
3. Install [MuJoCo](https://github.com/openai/mujoco-py) for Python.
4. Install a version of `torch` compliant with your GPU and CUDA. We for example install torch 1.11 for CUDA 11.3
using the following command:
```
pip install torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
```

## Running
Run the jupyter notebook at the root of this repository.