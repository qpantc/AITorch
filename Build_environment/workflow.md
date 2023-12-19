# conda environment

1. install miniconda: 
    ```bash
    wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    bash Miniconda3-latest-Linux-x86_64.sh
    eval "$(/home/quan/miniconda3/bin/conda shell.zsh hook)" 
    ```
2. creat d2l python environment
    ```
    conda create --name d2l python=3.9 -y
    conda activate d2l
    ```

# install package
    ```python
    pip install torch==1.12.0
    pip install torchvision==0.13.0

    # 经常使用的函数和类
    pip install d2l==0.17.6
    ```