# Voxelmamba

## Progress
* Semantic segmentation

* Install [MinkowskiEngine](https://github.com/NVIDIA/MinkowskiEngine#anaconda)  


```
sudo apt install g++-7  # For CUDA 10.2, must use GCC < 8
# Make sure `g++-7 --version` is at least 7.4.0
conda create -n py3-mink python=3.8
conda activate py3-mink

conda install openblas-devel -c anaconda
conda install pytorch=1.9.0 torchvision cudatoolkit=10.2 -c pytorch -c nvidia

# Install MinkowskiEngine
export CXX=g++-7
# Uncomment the following line to specify the cuda home. Make sure `$CUDA_HOME/nvcc --version` is 10.2
# export CUDA_HOME=/usr/local/cuda-10.2

```
