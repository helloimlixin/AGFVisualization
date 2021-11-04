# AGF-Visualization

Official code for "Attribution Guided Factorization for Neural Networks Visualization" 

Baseline methods are taken from [link](https://github.com/utkuozbulak/pytorch-cnn-visualizations), and [link](https://github.com/idiap/fullgrad-saliency).

## Prerequisites

- python 3.6
- pytorch 1.1
- torchvision
- numpy
- scipy
- scikit-learn
- scikit-image
- Pillow
- matplotlib
- OpenCV
- tqdm
- h5py
- imageio
- tensorboard

## Usage

1. Create a new conda environment:

   `conda create -n agf_env python=3.6`

2. Activate the created environment:

    `conda activate agf_env`

3. Update conda to keep track of the environment:

    `conda update --all`

4. Install the PyTorch library inside the conda environment just created per the [PyTorch official website](https://pytorch.org/get-started/locally/), for instance, using `conda` with cuda toolkit version 10.2 on a linux machine, we have the command to install the current Long-Term-Support (LTS) Version,

    `conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch-lts`

5. Install other required libraries if absent:

    ```shell
    pip install matplotlib
    pip install scikit-image
    pip install opencv-python
    ```

Good luck!
