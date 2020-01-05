# Removing black bars with a CNN

|      Epoch 0          | Epoch 1       |Epoch 2        |Epoch 3        |Epoch 4        |
|:--------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|![damaged_image](https://github.com/SibHusky/simple_CNN_watermark_denoiser/blob/master/data_model%231/valid_pic_10percent_%231_0_damaged.png)    | ![damaged_image](https://github.com/SibHusky/simple_CNN_watermark_denoiser/blob/master/data_model%231/valid_pic_10percent_%231_1.png)  | ![damaged_image](https://github.com/SibHusky/simple_CNN_watermark_denoiser/blob/master/data_model%231/valid_pic_10percent_%231_2.png)  | ![damaged_image](https://github.com/SibHusky/simple_CNN_watermark_denoiser/blob/master/data_model%231/valid_pic_10percent_%231_3.png)  | ![damaged_image](https://github.com/SibHusky/simple_CNN_watermark_denoiser/blob/master/data_model%231/valid_pic_10percent_%231_4.png)  |

The Jupyter Notebook "Denoiser#1" shows a simple CNN build with Pytorch. For the training the CNN needs 'damaged' images and the corresponding clean images. Therefore a second Jupyter Notebook ("data4denoiser") is available. This one takes a mp4 file and a watermark picture and out of that the watermarked and the clean images are taken. 

## Usage

All the python package comes with the Anaconda installation, except Pytorch and Open CV. So these two packages must be installed.
Pytorch:
https://anaconda.org/peterjc123/pytorch
Open CV:
https://stackoverflow.com/questions/24400935/how-could-we-install-opencv-on-anaconda

## Other files

Other files:
- a short mp4 video
- two watermark pngs
- an example of input image --> data4denoiser --> watermarked image

## Coming soon

A 3rd Notebook or python script that puts the denoised images together to a video file

## License

This is distributed under the MIT license.



