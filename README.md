# Fruit Detection System 

Fruits detection using color segmentation method in Matlab (Computer Vision) Code to detect plot different fruits in 1 picture. You can run the code with the picture "fruits.jpg", make sure you have the 2 files in the same directory. Feel free to suggest new versions of the code and new functionalities.This MATLAB code performs fruit segmentation in an image based on the Hue, Saturation, and Value (HSV) color space. It can identify and separate bananas, apples, oranges, and kiwis in an input image


## Prerequisites
MATLAB installed on your machine.

## Installation

1. Clone the repository to your local machine.

~~~bash
git clone https://github.com/your-username/fruit-segmentation.git
~~~

2. Open MATLAB and navigate to the project directory.

3. Open the main script file fruit_segmentation.m in MATLAB.

4. Modify the input image file path if needed.

~~~bash
im_IN = imread('path/to/your/image.jpg');
~~~

5. Run the script by clicking the "Run" button in MATLAB or entering fruit_segmentation in the MATLAB command window.


## Features

* HSV Color Space Conversion: The code converts the input RGB image to the HSV color space, facilitating better color-based segmentation.
* Fruit Segmentation: Utilizes specific HSV ranges to segment fruits (banana, apple, orange, kiwi) from the input image.
* Individual Channels Display: Displays individual channels (Hue, Saturation, Value) of the HSV color space for better visualization.
* Region Masks:Generates masks for each segmented fruit, highlighting their regions in the original image.
* Modular Segmentation: Segmentation parameters for each fruit are modular and can be easily adjusted for different images.
* Visualizations:Displays original and segmented images using MATLAB's subplot functionality for easy comparison.

  

## Output  

The code generates binary masks and segmented images for each fruit category, including banana, apple, orange, and kiwi. The output is displayed in a MATLAB figure with individual subplots.

![Output](https://github.com/Wisteriaa9/Fruit-Detection-MATLAB/assets/100563080/f1c22471-149a-4b10-ae15-e84997fde0cd)
