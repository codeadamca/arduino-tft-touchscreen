# arduino-tft-touchscreen
A basic example of displaying images using an Arduino and a TFT touchscreen.

## Steps

1. Format an SD card using MS-Fat.
2. Place a series of images in BMP format in the root of your SD card.
3. Place the SD card in the back of the TFT scrrn and unstall the screen touchscreen on the Arduino.

> Note: I'm using this [TFT Touchscreen](https://www.aliexpress.com/item/1874979237.html?spm=a2g0s.9042311.0.0.27424c4dE69kwA).

4. Open the Arduino IDE and open tft-images.ino.
5. Change the dimensions in the code to match your screen. Change the list of your image filenames.
6. Upload and run the code.

## Common Problems

### Image Format

The images on the SD card need to be BMP format. To get the images to work I had to open them in Photoshop, click Save as..., select BMP as the Format, click Advancd Mode on the BMP Options window, and then choose the first option (16 Bit X1 R5 G5 B5). 

### TFT Support

I usually use the online Arduino Web Editor; however, in this case I had to make a change to one of the libraries, and this is only possible when using the download verion of the Arduino IDE. I had to adjust the Mcufriend_kbv Arduino library to work with my component. I had some help from a fellow Arduino programmer on [how to do this](https://forum.arduino.cc/index.php?topic=714629.msg4801325#msg4801325).

## Tutorial Requirements:

* [Visual Studio Code](https://code.visualstudio.com/) or [Brackets](http://brackets.io/) (or any code editor)
* [Arduino Create](https://create.arduino.cc/editor) 

Full tutorial URL: https://codeadam.ca/learning/arduino-tft-touchscreen.html

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
