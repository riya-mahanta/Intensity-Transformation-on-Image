# Intensity-Transformaiton-on-Image
Applying different intensity transformation functions on a Mammogram image using python.


Notation: r β pixel intensity of the input image; s - pixel intensity of the transformed image; L β the maximum intensity of the input image (e.g., L = 256 for an 8-bit grayscale image)

1. Given the mammogram image πΌ (βMammogram.pngβ), compute its negative image πΌπ, using π  = (πΏ β 1) β π.

2. Apply log transformation onto the negative image πΌπ, i.e., π  = log (1 + π). (1pt)

3. Apply power-law transformation onto the negative image πΌπ, i.e., π  = π^πΎ. You can choose different πΎ to test it (e.g., πΎ = 0.1).

4. Apply the following piecewise linear transform for the contrast stretch on the negative image πΌπ, where ππππ is the 
minimum intensity value in the input image and ππππ₯ is the maximum intensity value in the input image.

![Screenshot (1)](https://user-images.githubusercontent.com/104661324/222622561-55936732-2111-452b-b8da-0d569f1aea11.png)

