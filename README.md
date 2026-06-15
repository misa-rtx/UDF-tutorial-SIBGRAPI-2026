# Neural UDF SIBGRAPI 2026 Tutorial
## Installation (Conda)
Create and activate the environment
```bash
conda env create -f environment.yml
conda activate neural-udf-tutorial
```
Check your NVCC version (we are currently using for CUDA 11.8)
```bash
nvcc --verison
```
If it doesn't look like this
```bash
nvcc: NVIDIA (R) Cuda compiler driver
Copyright (c) 2005-2022 NVIDIA Corporation
Built on Wed_Sep_21_10:33:58_PDT_2022
Cuda compilation tools, release 11.8, V11.8.89
Build cuda_11.8.r11.8/compiler.31833905_0
```
Go to https://github.com/jonstephens85/3DGS-WSL-Setup and set up your CUDA version. 
Install Pytorch version 2.5.0 with GPU enabled: 
```bash
PYTHONUSERSITE=1
pip install torch==2.5.0 torchvision==0.20.0 torchaudio==2.5.0 --index-url https://download.pytorch.org/whl/cu118
```
