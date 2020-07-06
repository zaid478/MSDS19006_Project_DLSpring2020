# Attention based multiple instance learning for medical image analysis

The code is majorly taken from [this](https://github.com/mahmoodlab/CLAM) repository. We have done all the experiments by modifying the referred base code.

## Dataset
The dataset can be found [here](https://warwick.ac.uk/fac/sci/dcs/research/tia/data/crchistolabelednucleihe/).

### Results

We have done two experiments on the dataset. Below are the train loss curves for both of them.
The first plot is the same as baseline CLAM model. The other is reflecting the change in loss function of clustering layer and sampling strategy.

![alt text](https://github.com/zaid478/MSDS19006_Project_DLSpring2020/blob/master/plots/v1/train_error.svg)

![alt text](https://github.com/zaid478/MSDS19006_Project_DLSpring2020/blob/master/plots/v2/train_error.svg)


Clustering layer loss for training is shown below for both of the experiments respectively

![alt text](https://github.com/zaid478/MSDS19006_Project_DLSpring2020/blob/master/plots/v1/train_clustering_loss.svg)

![alt text](https://github.com/zaid478/MSDS19006_Project_DLSpring2020/blob/master/plots/v2/train_clustering_loss.svg)

