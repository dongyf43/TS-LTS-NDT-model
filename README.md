# TS-LTS-NDT-model
Testing model for "Cao, Yanpeng, et al. "Two-stream convolutional neural network for non-destructive subsurface defect detection via similarity comparison of lock-in thermography signals." NDT & E International (2020): 102246“.

This code runs with Caffe deep learning platform, "Yangqing Jia, Evan Shelhamer, Jeff Donahue, Sergey Karayev, Jonathan Long, Ross Girshick, Sergio Guadarrama, and Trevor Darrell. Caffe: Convolutional architecture for fast feature embedding. arXiv preprint arXiv:1408.5093, 2014"

You can download testing data at https://pan.baidu.com/s/1thciN12GHHxeLU8pivfo2g with extract code 'ixya'. Data is stored as .mat by Matlab and it contains infrared sequences with three materials (AL. steel and CFRP) and four frequencies (0.025, 0.05, 0.075, 0.1Hz). All sequencies is 380*380*2000 pixels and they have been distortion corrected and detrended.

If you find this code helpful, please consider to cite our work:

@article{cao2020two,

  title={Two-stream convolutional neural network for non-destructive subsurface defect detection via similarity comparison of lock-in thermography signals},
  
  author={Cao, Yanpeng and Dong, Yafei and Cao, Yanlong and Yang, Jiangxin and Yang, Michael Ying},
  
  journal={NDT \& E International},
  
  pages={102246},
  
  year={2020},
  
  publisher={Elsevier}
  
}
