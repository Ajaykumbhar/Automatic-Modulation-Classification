# Automatic-Modulation-Classification (AMC) for Low Powered IoT Devices

## What is Automatic-Modulation-Classification ?
- Automatic modulation classification (AMC) is used to identify the modulation for the received signal. IoT devices use modern communication methods which are based on multiple input multiple output (MIMO) in which the signals are received from various sources. The identification of modulation is vital. 

## Abstract
#### In this work, we investigate the value of employing deep learning for the task of wireless signal modulation classiﬁcation. We consider a baseline method using cumulants and compare it with the deep learning approach across a varying range of signal-to-noise ratios. We have use  three type of Deep  architecture.
## Those are :
- - 1. Artificial Neural Networ(ANN)
- - 2. convolutional
- - 3. Recurrent Neural Networks(RNN).
##  The final number of parameters of each model was considered during thedesign phase, as it can have a big impact on a memory footprint of a deployed model.The architectures were written in Keras, which is a software library, which provides a Python interface for neural networks. The results of the architectures were additionally compared to results from other research papers on this topic.


## Dataset Used
### RadioML Datasets
- O'shea, Timothy J., and Nathan West. "Radio machine learning dataset generation with gnu radio." Proceedings of the GNU Radio Conference. Vol. 1. No. 1. 2016.

- The datasets are available at: https://www.deepsig.ai/datasets

- All datasets provided by Deepsig Inc. are licensed under the Creative Commons Attribution - NonCommercial - ShareAlike 4.0 License (CC BY-NC-SA 4.0).

- Both datasets are left unchanged, however, the RadioML2016.10b version is not stored as the original data, but is already splitted into X and labels
