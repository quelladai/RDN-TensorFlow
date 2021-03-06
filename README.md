# RDN-TensorFlow
A TensorFlow implementation of CVPR 2018 paper [Residual Dense Network for Image Super-Resolution](https://arxiv.org/abs/1802.08797).
  
## Prerequisites
- Python 2.7
- Numpy
- TensorFlow
- OpenCV
- h5py
  
## Usage
### Prepare data
Download DIV2K training data from [here](http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_train_HR.zip).  
Extract and place all the images in RDN-TensorFlow/Train/DIV2K_train_HR.
### Train
`python main.py`
### Test
`python main.py --is_train=False`
  
## References
- [kweisamx/TensorFlow-ESPCN](https://github.com/kweisamx/TensorFlow-ESPCN)
