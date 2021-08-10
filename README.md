# VCD-dependent-traffic-control-signal

In this VCD stands for Vehicle Congestive Density.
We will be finding the density of the road and accordingly we will assign the timing for signals.

so, we will be considering an EMPTY image and Traffic road image, we will detect the edges by 'Canny edge detection method' and we compare those to images then if the match value is more then the is more traffic else vicivoce.

before applying the edge detection we will be doing various operations on images to get better edges.

Firstly download the input images which u need to input for the code when u run it.

There are different functions which are used in this project, which are given in function folder.

after running the code you will get the different windows with different operations applied on 4 input images and also the edge detected images window. 

lastly we get the image which is having highest match and same road will be released to control the traffic.
