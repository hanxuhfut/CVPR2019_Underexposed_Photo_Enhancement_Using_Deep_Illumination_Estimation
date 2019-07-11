# Underexposed Photo Enhancement Using Deep Illumination Estimation

[Ruixing Wang](http://appsrv.cse.cuhk.edu.hk/~rxwang/)<sup>1</sup>, [Qing Zhang](http://zhangqing-home.net)<sup>2</sup>, [Chi-Wing Fu](https://www.cse.cuhk.edu.hk/~cwfu/)<sup>1</sup>, [Xiaoyong Shen](http://xiaoyongshen.me/)<sup>3</sup>, [Wei-Shi Zheng](https://sites.google.com/site/sunnyweishi/)<sup>2</sup>, [Jiaya Jia](http://jiaya.me/)<sup>1,3</sup>

<sup>1</sup>The chinese university of hong kong <sup>2</sup>Sun Yat-sen University <sup>3</sup>Tencent Youtu Lab

## Thanks to the original author for sharing the code. This is my own modified version. Please refer to the author's [homepage](https://github.com/wangruixing/DeepUPE) for details.


## I modified the main/Makefile so that the compilation is successful. The modified "Makefile" is already in ‘main’ and I have compiled it in ‘build’.

1.
```shell
Python 2.7, Ubuntu 14.0, gcc-4.8, GeForce GTX TITAN X.
```
2.
```shell
1) cd main
2) pip install -r requirements.txt
3) make
```
3. Evaluation:
The test set can be downloaded in https://drive.google.com/file/d/1HZnNgptNxjKJAhekz2K5yh0mW0yKIws2/view?usp=sharing. It includes 500 pair images from MIT-Adobe FiveK 4500-5000. You can download this and run:
```shell
    python main/run.py checkpoints <input file path> <output file path>
```    
PSNR evaluation code is in avg_psnr.m. Modify the related paths in 'avg_psnr.m', and run it.




# Bibtex
```
@InProceedings{Wang_2019_CVPR,
author = {Wang, Ruixing and Zhang, Qing and Fu, Chi-Wing and Shen, Xiaoyong and Zheng, Wei-Shi and Jia, Jiaya},
title = {Underexposed Photo Enhancement Using Deep Illumination Estimation},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2019}
}
```
