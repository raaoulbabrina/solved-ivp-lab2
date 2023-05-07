Download Link: https://assignmentchef.com/product/solved-ivp-lab2
<br>



<strong>Q1. </strong>Consider the figure below and the problem of matching a given image template (ex. Image with symbol ‘K’) to different regions/objects in a target image (the bigger image with many symbol). Based on the techniques studied till now, try implementing a method to locate the region in the target image which matches with the template image.

<strong>Q2. </strong>Consider Roberts, Prewitt, and Sobel filters (gradient operators shown in left figure), Laplacian filters (shown in the right image). Apply these filters on barbara.jpg and make observations upon comparing their outputs. Do the same for a suitable image of your choice.

<strong>Q3. </strong>Try to enhance the ‘skeleton.jpg’ image by performing sequence of operations as discussed in the textbook/class or any other alternative method.

<strong>Q4. </strong>(a) Find (or develop) a program to add Gaussian noise to an image. You must be able to specify the noise mean and variance. (b) Find (or develop) a program to add salt-andpepper (impulse) noise to an image. You must be able to specify the probabilities of each of the two noise components.

<strong>Q5.  </strong>Identify noise and apply suitable filter to recover the original images (a, e) from the given noisy images (b, c, d and f, g) respectively.




(a)                                          (b)                                              (c)







(d)







(e)                                                          (f)                                                              (g)




<strong>Q6.</strong> Image 1 (<strong>img1noisy.tif</strong>) contains impulsive noise (left side) and additive white gaussian noise (right side). Try to use a median filter and a mean filter. Calculate the mean-square error:

(where Io is the original/noise-free image and If the noisy/filtered image), in both sides separately of the image both before and after filtering with the different filters. Compare and discuss both the numerical results and visual appearance. Finally, show ‘the best possible’ filtered image, where both the left and the right side are filtered with the filter that produces the minimum mean-square error. Show also the respective error image (i.e. the difference image between the original and the corrected image). (Remember to scale the error image properly!). The original noise-free image is in the file ‘<strong>img1original.tif</strong>.’