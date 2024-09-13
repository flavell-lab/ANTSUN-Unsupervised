# ANTSUN-2U (Unsupervised)

The notebook `ANTSUN_2U.ipynb` performs unsupservised NeuroPAL neuron labeling. It takes as input a fully-trained CellDiscoveryNet and a directory containing 4-D multispectral images of worms, their ROI (segmentation) images, and Euler-registered versions for every pair of images.

## Installation

See [the base ANTSUN pacakge](https://github.com/flavell-lab/ANTSUN) for installation instructions.

## Usage

This code assumes you have already run the [`make_CellDiscoveryNet_input.ipynb` notebook](https://github.com/flavell-lab/DeepReg/tree/main/CellDiscoveryNet/make_CellDiscoveryNet_input.ipynb) and [trained CellDiscoveryNet](https://github.com/flavell-lab/DeepReg/tree/main/CellDiscoveryNet/train_CellDiscoveryNet.ipynb).

## Citation

If you are using this code, please cite the following article:

#### Deep Neural Networks to Register and Annotate the Cells of the *C. elegans* Nervous System
Adam A. Atanas, Alicia Kun-Yang Lu, Jungsoo Kim, Saba Baskoylu, Di Kang, Talya S. Kramer, Eric Bueno, Flossie K. Wan, Steven W. Flavell

bioRxiv 2024; doi: https://doi.org/10.1101/2024.07.18.601886

