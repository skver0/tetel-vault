# Transfiguration(Signal conversion) and coding
--- 

### Concepts of analogue and digital signal, examples of their use
 - An analogue signal is a continuous/infinite signal, since it varies continuously with what it represents. within a defined range, and time interval, it can turn into any value. Its domain of interpretation and its set of values are infinite. 
 - Some examples: 
	 - traditional clock (the hands change with the time), 
	 - traditional speedometer (the hands change with the the pressure on the accelerator)
	 - conventional thermometer (the mercury rises with the temperature)
	 - hourglass (the sand rolls down from the top to the bottom over time)
 
 - digital
	- With digital signals we only use numbers, and we only extract signal in a finite interval, such that we can properly, and efficiently process it for our needs(analog signal is basically infinite, and we of course cannot process infinity in a finite time). 
	- digital signal always needs to be encoded and decoded between the sender, and reciver, because digital signal can only be efficitently read by computers, but digital data have to be encoded into eletrical, or optical signal in order to be transported, and then decoded to be processed as digital signal again for computers.
	- Timeline discrete signal: the interpretation range of the signal is discrete, its set of values is continuous
	- Discrete signal in amplitude: its range of interpretation is continuous, but its set of values is discrete
--- 
### Difference and characteristics of the analogue and digital signal
- The difference between "digital" and "analogue" is the input, the storage of data, the transmission, and display method
---

### The digitalisation of analogue signals
- 1. Sampling
	-  If an analogue signal needs to be converted into digital, it is done by so-called "sampling": at certain intervals (like, for sounds or images) a "sample" of the signal state is taken and stored digitally (from a pool of infinit amount of analog signal).
	- This signal can take an infinite number of values along the y-axis (the set of values)
	- the range of interpretation is reduced
- 2. Quantization
	- Quantization is the transformation of infinitely many possible values into finite values that are rounded to a selected value(like integer, decimal and many more).
	- The quantization process produces the digitized signal.
	- During quantization, the measurement range is divided into finite intervals, and signal values are set within it.
	- The value established on the basis of the sample values are decreased in some cases increases i.e. the quantization adds noise to the original signal.
		- The quantized signal carries no information about how much noise was added.
- 3. Encoding
	- The purpose of encoding is computer is storing the extracted data, into such data, that can be processed by computers efficiently.
	- Converts the extracted signal into binary form, by assigning it a series of ones and zeroes.
- Types:
	- PCM - assigns a unique code for each quantization level
	- DPCM - a code is assigned to the deviation from the previous sample
	- Predicted DPCM - describes the deviation from the expected value based on the previous sample series
---
### The law of sampling
- Shannon formulated the law of how often a continuous signal should be sampled to recover the original signal from the sampled signal sequence. Based on Shannons law, if we want the samples to properly represent the spectrums component with the largest frequency, the sampling frequency has to be at least twice the size of the spectrums component's with the largest frequency.
	- For Example, the human ear can hear up to 20 000 khz, and the most common sampling frequency of audio signals(via microphone), is 44 000khz because it is at least twice as larger than 20 000khz, so it must represent the whole 20 000khz spectrum properly, so that it could be turned back into analog signal without issues.
---

### Digitisation of sound, image and film
- Image digitalization
	- the visible image is essentially analogue information. 
	- the first step in the computer processing of images is the processing the visual light of an image into digits (digitisation). This is done by scanners and digital cameras.
- types
	- Black-and-white scanning: if the reflected light intensity is below a certain limit, the pixel is black (0), otherwise white (1).
	- Greyscale scanning: corresponds to a shade of grey depending on the intensity of the reflected light. The color of a point can be assigned from 0 to 255 (256 shades of grey).
	- Colour scanning: the colour filters of the sensors breaks down the reflected "mixed colour" light into a mix of red (R), green (G) and blue (B) values, so that the rgb values transmitted to the computer shows a single color. There is a set of 255 shades for each red green blue color (255<sup>3</sup> ≈ 16 million colours).
	- The quality of the digitised image also depends on the resolution of the scanner, measured in DPI (dots per inch, or the number of pixels per inch).
		- hardware (real) resolution: what the scanner is capable of through its optical system
		- software resolution (interpolated) : increasing the number of pixels by calculation, which doesen't enhance the image

-  The digital camera also produces a raster image.
	- by changing setting the exposure time, how long the lense is opened, and how long the cameras light censor allowed to recieve light, the light censor's millions of tiny light sensnitive cells detect light.
	- before the light censor, with different filters usually 50% green, 25% red and 25% blue the image is altered
	- with the help of these filters and light censor, each cells value is digitized, saved, and stored into serieses of rgb values, with the place of each pixel within the matrix also saved
	- the resolution of an image is called megapixel (product of vertical, and horizontal lines i.e. 1920 by 1080)
---
### Sound digitisation
- steps are very simular to other analog signal digitisation
- sound also has to be encoded and decoded when transporting the data between computers
- encoding of sound signal is done by a ADC module (analog to digital convereter) 
- decoding is done by a DAC module (digital to analog converter)
- Shannon's law applies here as well. That's why CD quality is at least 44100 hz commonly
- Another characteristic that determines the quality of sound is the bit depth. Bit depth determines how much of the audible spectrum (from about 20 Hz to 18-20000 Hz) we can process as computer data.
---
### Tools for digitisation
- Scanner
- Digitising table
- Photocamera
- Video camera
- Microphone
---
### The concepts of data and data volume in informatics
- definition of data:
	- In computer science, data is defined as a set or sequence of signals represented in some kind of signalling system that can be recorded, processed and displayed, i.e. interpreted, by some computing device. Data can be stored in any form that can be interpreted.
- definition of data volume
	- data volume is a quantity that measures the number of signals in a chosen signalling system and corresponds to a unit of measure.
---
### Units of measurement used in informatics and their characteristics
- The unit of the data is 1 bit (binary digit - 0/1). 1 byte = 8 bits, the conversion from 1024: KiB (kibibyte), MiB (mebibyte), GiB (gibibyte), TiB (tebibyte), PiB (pebibyte)... Or the more commonly used 1000 conversion: kB (kilobyte), MB (megabyte), GB (gigabyte), TB (terabyte), PB (petabyte), EB (exabyte).
- some conversions for reference
	- 1 GB = 8 Gbit = 1 000 MB = 8 000 Mbit = 1 000 000 kB = 8 000 000 kbit = 1 000 000 000 B = 8 000 000 000 bit
	- 1 GiB = 1024 MiB = 1 048 576 KiB = 1 073 741 824 B = 8 589 934 592 bi
	- The example above shows how much difference there can be between a conversion of 1000 and 1024 for larger amounts of data. This is often exploited, for example, by harddrive, ssd etc. manufacturers or Internet service providers. This is why, for example a 1 TB hard disk is actually only 976 GiB, even less after partitioning, and you don't actually get the full 1 TB of space.
---
### Binary number notation method and its importance in computer science
- representing integer numbers (on 1 byte, 8 bits):
	- A limited number of bits can be used to represent numbers.
	- integers in binary are reprented as 2<sup>1</sup>, 2<sup>2</sup>, 2<sup>3</sup>, 2<sup>4</sup>, etc.
		- for exampas starting from 2<sup>0</sup>, all the le 0 1 0 0 1 1 1 1 equals to 79 as 1 + 2 + 4 + 8 + 64 = 79 (from right to left, counting each 1, way to 2<sup>7</sup> )
		- To convert a number into a number base 10, we need to add them together.
	- The numbers can be divided into two parts:
		- signed: (+ or -) so from -128 to +128 thus we get the 0-255 range on 1 byte
		- unsigned: (+ only) from 0-255 range on 1 byte
	- representing integers is not limited to 8 bit, it can even be 32 bit.
- Representing real or floating point numbers
	- Often, we are not able to represent an exact value, so we will treat it as an approximate value.
	- The byte where the number is handled is divided into two parts and wtih 1 bit if it's negative or positive number: 
		- mantissa, and characteristics : 
--- 
### Forms of binary character representation, structure and characteristics of code tables (ASCII, UNICODE)
- coding: when according to sets of rules, converting characters from a set to another set like: from ASCII to UNICODE
- types:
	- reversable: when you can convert the date back and forth.
	- irreversable: when you cannot convert it back and forth.
- examples of code systems/sets: morse, punch card, digitising sounds or images
- character sets:
	- CCITT - This is the very first character set that allowed 32 characters to be represented. 
	- ASCII –  Contains all the letters used in the English alphabet, as well as the most common punctuation marks. The character set contains 128 characters. 
	- UNICODE - An international standard, includes characters from most languages, and is based on 16 bit, which is around 100 000 characters
	- UTF-8 – In contrast to the full UTF-32 encoding, which takes up 4 bytes per character, the more compact (1 byte) UTF-8 encoding is the most common. UTF-8 is a variable-length encoding (8 to 64 bits) that represents the Unicode character table. It is fairly common on Linux systems, but on Microsoft Windows upwords of xp is also fully supported. The IETF (Internet Engineering Task Force) Internet protocol demands, while using the protocol, utf-8 must be included in the possible character sets.
---
### Storage of digital images, image formats and their characteristics (raster and vector)
- Raster illustration:
	- An image is made up of a set of pixels arranged in columns and rows. The number of columns and rows given is the resolution of the image (e.g. 1920×1080, the image is 1920 pixels wide and 1080 pixels high). 
	- The color of each pixel has to be stored. The color quality of an image is determined by its colour depth, i.e. how many colours are selected from a palette of colours. the colour of the pixels.
	- When saving, information about the image in different formats (BMP, GIF, JPG, etc.), a lot of diffrerent things are  written to the header of the file including color depth, so the actual space occupied is slightly larger than the actual size of the image.
	- 4 bit: 16 colours, 8 bit: 256 colours, etc.
	- The real solution is the RGB colour model, with 16 million colours. 
- vector image:
	- Another type of graphic type are vector images, which are used primarily for displaying drawings, geometric shapes that can be described by geometric formulas. The image file contains only the information needed to produce the image.
	- It's advantage is small space requirements, and flexible scaling, without any quality loss (since it isn't defined in a fixed coordinate system)
	- Vector graphics images are better quality, more editable and take up less space, but they are not suitable for real life images.
- some image formats:
	- without compression:
		- BMP
		- TIFF 
		- RAW - fully lossless, clean, very large size
	- with compression:
		- JPEG - more agressive, lossy
		- PNG - less loss in image quality
		- GIF 
---
### Ways of color coding
- RGB 
	- In the RGB colour system, colors are created by adding the three primary colours red, green, blue. This is an additive colour mixing. This type of colour mixing system is based on the emitted or perceived light and can only be created by light-emitting devices (e.g. monitors). If all three colors are projected in "maximum quantity", white light is displayed, otherwise black.
	- 3 bytes are used, 1 for each color, which sets how much of each color should be added (ie: 255 255 255 is pure white)
	- 3 bytes are 24 bit, so there's 16 million+ colors possible with this system
- CMYK:
	- When printing colored images, the CMYK model is used. Unlike RGB, this is not additive but subtractive colour mixing.
	- Consists of cyan, purple, yellow, and black
	- it consitst of 4 byte, which is 32 bit 

