# Transfiguration and decoding
---
-  analog
	- phisical matter, commonly electric signals, used to represent some sort of data in a continous, infinite manner between devices. Data can be represented by a wide variety of ways like: wavelength, length of a continious signal, voltage, or even pressure. 
-  digital 
	- the data is represented strictly in numerical form, which is decoded and encoded between computers, commonly transported via electrical, or optical form.
---
### Difference between digital and analog signal:

-  way of storage 
	-  digital data can be stored with many 1 and 0, analog data cannot be stored only converted into digital, and stored as digital.
-  way of transporting 
	- analog data can be transported in a wide variety of creative ways, due to it's phisical nature.)
-  way the signal is displayed 
	- humans have a very hard time reading base 2 data, due to it's length, but analog signal can more easily be represented by, for example: waves, mathematical graphs, and many more.
---
### Converting analog signal into digital (in steps)

##### (1<sup>st</sup>)  Sample extraction \ sampling
- in given instances taking a sample from the signal using different instruments, and storing this data in some way, usually in numerical form.
- some sampling techinques: 
	- natural sampling (keeps the natural shape of the signal)
	- flat top sampling (easier to implement, most common technique, not as accurate)
	- ideal sampling (very detailed, the sampling frequency is very large, but is hard to implement, and is processing heavy)
##### (2<sup>nd</sup>)  Quantization 
- the stored signal has to be rounded, simplified, and compressed, for easier and practical storage.
##### (3<sup>rd</sup>)  Encoding 
- transforming the simplified data into binary data (stored as bytes), this process varies quite a bit, and is done with varrying techniques for the most optimal proccessing for the specific tasks.
- **Laws of sampling**: According to the Nyquist-Shannon theorem, the sampling rate must be at least 2 times the highest frequency contained in the signal. 
	- Example in the real world: the human ear can only hear at max around 20k hz, and the sampling rate for audio in 	microphones is usually at least 44k hz, but usually more, thus for the human hearing sound can be digitized without any humanly precivable dataloss.
- **Sound, image, and video digitalization**
	- The scanner or camera, breaks down the incoming light into matrixes, and assings a color value to each and every pixel, and in advanced cameras additional data like color depth among many other things.
	- This raw data is then processed and stored.
	- Basic image types: Binary image, Black and white, 8-64 bit color format (color values assigned as rgb value (each color with a 0 to 255 value for each color red green blue. for example. (0, 77, 255) )
	- Digitized images are stored as a count of pixels, called resolution.
- **Sound digitalization:** 
	The job of digitalization is the work of the **ADC module** (analog to digital converter module) found on all soundcards, and the playing of the audio is the job of the **DAC module** (digital to analog converter module). 
	The ADC samples the signal, quantitaizes it, as a count of hertz, and encodes it, and the DAC does the same but in reverse, which must be done because speakers are playing analog signal, while computers need digital signal, so this main conversions is always needed.
- **video digitalization**
	- video digitalization by nature is very similar to image digitalization difference being, while with images one single image needs to be digitized, but in video thousands upon thousands of images need to be digitized with indexes attached, in a way that a computer knows which one should be played after each image, to create the video, and in what speed (for example 30 or 60 times per second.)
- **Instruments of digitalization**: scanner, digitalization table, cameras, video cameras, microphones, and many more.
---
### Data as in informatics.
- data in computers is strictly used as digital, binary form.
-  binary form is represented as ones and zeroes, digital datas smallest unit is 1 byte which consists of 8 bits and expands in 1024 intervals to kilobyte, megabyte, gigabyte etc., as 1 megabyte is 1024 kilobytes and so on. 
- binary data is transported, as electrical or optical shortbursted signals, for example in electricity ones an zeros can be represented as changes in voltages, higher voltage 1 lower voltage 0.
- 1 byte can be represented as the variations of 2^1, 2, 3, 4, 5, 6, 7, 8, 9 which will be the sum of the mentioned 1024
	- we can represent these integers with prefixes like '-' and '+'
	- with '+' or '-' prefixes we can repsent numbers from -128 to +128 on 1 byte
	- without prefix, we can from 0 to 255 on 1 byte.
- In binary form, characters can be represented in bytes in for example ASCII or unicode table.
- **Character sets:** 
	- CCITT (the first ever set, can represent 32 different characters)
	- ASCII (American standard code for information interchange) is the english ABC letters + most common characters, represented in binary form
	- UNIOCODE first 128 value which is the same as ASCII but on 16 bits, around 100K characters can be represented (2^31) 
	- UTF-8 (8 bit unicode transformation format), has different types for 16, 32, and 64 bit 
- **digital images:**
	- Formatted in different file types, which have different characteristics, and is optimized for different things like size, image quality, proccessing diffuculty, etc.
		- JPEG 
		- PNG
		- TIFF
		- RAW 
		- and many more
- **Digital audio:** (basically works the same as images but for audio, and is each type is used for different optimalizations)
	- Formats: 
		- FLAC
		- WAV 
		- MP3
		- AAC and many more