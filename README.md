# Underwater-image-re-enhancement
Underwater image re-enhancement with the blend of simple color balance and contrast limited adaptive histogram equalization algorithm
In this we enhance the underwater images with the help of simple color balance to enhance the images by using affine transformation with the help of percentile stretching and the
output of the image by simple color balance is given input to the clahe algorithm it enhance the contrast of the image by using clip limit divide the image into regions to contrast individually and then merge the images by shaprening the borders and display the enhanced images after that calculate the evaluation metrics in which to describe the visual metrics thorugh different metrics such as peak signal to noise ratio(s/n) and structural similarity of index and underwater color image quality evaluation and root mean square to evalaute the metrics.
After i done a comparision pdf which contains three type of images :

First type is original images in this i calculate the psnr values for all models such as GAN,RAHIM,MSRCR,SCB,CLAHE and also i perform combinations with rahim and simple color balance and rahim with clahe and vice-versa
And also i calculate the ssim values with individual along with combinations and also uciqe values with individual and combinations for the original images.


Second type is moderate images in this i calculate the same type of metric calculations along with other metrics such as ssim and uciqe to observed the dominated result.


And also the third type is blurred images in this also i calculate the individual and combinations metrics by using psnr and ssim and uciqe to observe the dominated result.
