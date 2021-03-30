# Prokudin-Gorskii-Collection
Image processing techniques to enhance the images in Gorskii’s collection.
I use image processing techniques to enhance the images in Gorskii’s collection. In order that
enhancement, my application splits the three color channel images, divides the image into three
equal parts and aligns the green and red to the blue one by calculating the best displacement
vector that was used to align the parts.
By splitting channels, we divide 3 components that are red, green, blue, into images.
This provides us on bit level slicing for each components.
Purpose of alignment is to find the possible displacement vectors. It scores the
displacement and takes the best score. SSD and NCC methods can be used to the alignment. In
my code, both of the methods exists and usable. But I run my code with ‘SSD’ algorithm.
