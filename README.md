# Image Artistic Styler
This is an implementation of styling a image by mixing n input image with the stye of another image why still preserving the content of our input image

A somewhat similar implementation of how the **prisma** app works

To solve this, the problem at hand is simplified as an optimization problem of style and content. Style well is the style of the image and content is what we actually view in the image.

In order to successfully art our images we need to be able to mix our image's with the style of another image while trying to preserve the contents of our image. In the code at step 6 are some weights that influence how much content and styel we want to preserve from the original image and as well the total variation from the original image.

The mathematics and science behind these can be found in the following 2 papers

[Karen and Andrew Very Deep CNN for large Scale Image Recognition](https://arxiv.org/abs/1409.1556)

[Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)

Motivation behind it all, what better way to introduce myself to computer vision and convolution nets other than this. And also reading and being able recreate results from scientific research papers

I've tried my best to comment and explain each step as easily as possible so if your new to this you might be able to easily flow
