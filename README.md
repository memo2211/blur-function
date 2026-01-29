# blur-function
This MATLAB function takes a grayscale image and applies a blurring effect.
Steps it performs:
Converts the input image to double for precise calculations.
Iterates over every pixel in the image.
For each pixel, it defines a square neighborhood of size 2w+1 centered at that pixel.
Calculates the average of all pixels in that neighborhood.
Assigns this average to the corresponding pixel in the output image.
Handles image edges by using only valid pixels inside the image boundaries.
Converts the final blurred image back to uint8.
Result:
A blurred version of the input image where each pixel is replaced by the average of its neighbors.
The larger the w value, the stronger the blur.
