# Removing watermarks with a CNN, Denoiser1 Jupyter Notebook

The Jupyter Notebook "Denoiser1" shows a simple CNN build with Pytorch. For the training the CNN needs watermarked images and the corresponding clean images. Therefore a second Jupyter Notebook ("data4denoiser") is available. This one takes a mp4 file and a watermark picture and out of that the watermarked and the clean images are taken. 

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



