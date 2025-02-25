# TS-LTS-NDT-model
Testing model for "Cao, Yanpeng, et al. "Two-stream convolutional neural network for non-destructive subsurface defect detection via similarity comparison of lock-in thermography signals." NDT & E International (2020): 102246“.

This code runs with Caffe deep learning platform, "Yangqing Jia, Evan Shelhamer, Jeff Donahue, Sergey Karayev, Jonathan Long, Ross Girshick, Sergio Guadarrama, and Trevor Darrell. Caffe: Convolutional architecture for fast feature embedding. arXiv preprint arXiv:1408.5093, 2014"

You can download testing data at https://pan.baidu.com/s/1thciN12GHHxeLU8pivfo2g with extract code 'ixya'. Data is stored as .mat by Matlab and it contains infrared sequences with three materials (AL. steel and CFRP) and four frequencies (0.025, 0.05, 0.075, 0.1Hz). All sequencies is 380*380*2000 pixels and they have been distortion corrected and detrended.

If you find this code helpful, please consider to cite our work:

```
@article{CAO2020102246,<br>
title = {Two-stream convolutional neural network for non-destructive subsurface defect detection via similarity comparison of lock-in thermography signals},<br>
journal = {NDT & E International},<br>
volume = {112},<br>
pages = {102246},<br>
year = {2020},<br>
issn = {0963-8695},<br>
doi = {https://doi.org/10.1016/j.ndteint.2020.102246},<br>
url = {https://www.sciencedirect.com/science/article/pii/S0963869519306498},<br>
author = {Yanpeng Cao and Yafei Dong and Yanlong Cao and Jiangxin Yang and Michael Ying Yang},<br>
keywords = {Non-destructive testing, Lock-in thermography, Convolutional neural network, Similarity comparison},<br>
}<br>
```
