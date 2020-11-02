# Image-Denoising

> This work has been done as a part of Master Thesis Intern Exam. Due to time bound, some specific comparison has been done.
> And, It is implemented on Google Colaboratory in Tensorflows-Keras.

It is a comparison of DnCNN and DIDN denoising model.


The implementation is based on: [https://github.com/SonghyunYu/DIDN] for DIDN architecture.

The implementation of DnCNN is based on: [https://github.com/cszn/DnCNN/blob/master/TrainingCodes/dncnn_keras].



Here, BSD500 color images are used for training and tested on CBSD68 dataset.

## File Descriptions

`Data_preparation.ipynb` - This file is common for both the architecture to do the preparation of data for training. 

`DnCNN_training.ipynb` - It is used for training of DnCNN architecture.

`DIDN_training.ipynb` - It is used for training of DIDN architecture.

`DnCNN_testing.ipynb` - Here, CBSD68 data are tested on DnCNN trained model having different noise values.

`DIDN_testing.ipynb` - Here, CBSD68 data are tested on DnCNN trained model having different noise values.

## References
<a id="1">[1]</a>
Songhyun Yu, Bumjun Park, and Jechang Jeong. Deep iterative
down-up CNN for image denoising. In: IEEE Computer Society
Conference on Computer Vision and Pattern Recognition
Workshops 2019-June (2019), pp. 2095-2103. issn: 21607516.
doi: 10.1109/CVPRW.2019.00262.

<a id="2">[2]</a>
Kai Zhang et al. Beyond a Gaussian denoiser: Residual learning
of deep CNN for image denoising”. In: IEEE Transactions on
Image Processing 26.7 (2017), pp. 3142-3155. ISSN: 10577149.
doi:10.1109/TIP.2017.2662206.
