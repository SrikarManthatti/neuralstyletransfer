# neuralstyletransfer
In this neural style transfer, I will generate a new image which contains the content from one image and contains style from the different image. In this project I will be using deep learning technique Convolution Neural Network to perform this Neural Style transfer

For this program to run you need to have the pre trained model of VGG-19, you can download this model from the 
https://www.floydhub.com/floydhub/datasets/imagenet-vgg-verydeep-19

and then create a folder named pretrained-model and pace the pretrained model in that folder.

If you want to upload your own images for the NST, then upload them onto the images folder and provide the respective path while reading the content and the style images in the program.

```python
content_image = scipy.misc.imread("images/your_content_image.jpg")
style_image = scipy.misc.imread("images/ypur_style_image.jpg")
```

Make sure that the images are of the width 400 and height 300px.
