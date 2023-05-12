# DaMFFN
This is the code to the Visual Computer paper "A Dual-Structure Attention-Based Multi-Level Feature Fusion Network for Automatic Surface Defect Detection" by Xiaoyu Zhang, Jinping Zhang, Jiusheng Chen, Runxia Guo and Jun Wu.

## Getting Started
You will need Python 3.6 and the packages specified in requirements.txt. We recommend setting up a virtual environment with pip and installing the packages there.

Install packages with:

`$ pip install -r requirements.txt`

## Configure and Run
All configurations concerning data, model, training, visualization etc. can be made in config.py. The default configuration will run a training with paper-given parameters on the provided dummy dataset. This dataset contains images of 4 squares as normal examples and 4 circles as anomaly.

To extract features, run extract_features.py (this was already done here for the dummy dataset, features were extracted to data/features). To start the training, just run main.py! Please report us if you have issues when using the code.

## Data

## Citation
Please cite our paper in your publications if it helps your research. Even if it does not, you are welcome to cite us.

    @inproceedings { RudWeh2022,
    author = {Marco Rudolph and Tom Wehrbein and Bodo Rosenhahn and Bastian Wandt},
    title = {Fully Convolutional Cross-Scale-Flows for Image-based Defect Detection},
    booktitle = {Winter Conference on Applications of Computer Vision (WACV)},
    year = {2022},
    url = {arxiv},
    month = jan
    }

## License
This project is licensed under the MIT License.
