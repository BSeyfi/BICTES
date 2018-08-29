![](https://user-images.githubusercontent.com/42473071/44986714-f7f9cb00-af99-11e8-9649-ee6b439432cd.png)
# BICTES
**BICTES** is a tool for compress 1-bit bitmap images for use in embedded systems.( jpg, png and bmp files ,colorful ,grayscale  image or 1-bit bitmap can be used as input image)

- - - -

Memory and also computing power in embedded systems are in tight conditions so it is a need to make images as small as we can but simple to decompress. BICTES do this job.
BICTES creates an array of `char` (replaceable with `uint8_t`) for use in `C` or C-like languages.

**BITSEC** is designed for make data array from image to use in embedded systems on black and white LCD displays.
<br/>

![bictes-sample](https://user-images.githubusercontent.com/42473071/44806056-18f99f00-abdb-11e8-8715-7d70a1c6d466.jpg)


- [Installation](#installation)
- [Features](#features)
- [License](#license)
- [Acknowledgment](#acknowledgment)

## Installation
Download `BICTES.exe` from `Release` folder and run.<br/>
Quick link to `.exe` file : https://github.com/BSeyfi/BICTES/blob/master/Release/BICTES.exe<br/>
Software needs `.Net Framework 4.0` or later has been installed.

## Features
- Compress image into 1-bit bitmap images based on **[bicolor image compression protocol for embedded systems](http://github.com/BSeyfi/bicolor-image-compression-protocol-for-embedded-systems)**
- Convert colorful or grayscale image to 1-bit bitmap image without compression(you can save it and use it  separately)
- Produce compressed or uncompressed image array in `C` or C-like languages array format - each byte is equivalent to 8 vertical pixels
- Show compression ratio - for show is compression is useful for that specific image or not

## License
This software is provided as Freeware for private non-commercial or educational use, including non-profit organization.
COPYRIGHT (c) 2018 Behzad Seyfi , All rights reserved
## Acknowledgment
1. **[bicolor image compression protocol for embedded systems](http://github.com/BSeyfi/bicolor-image-compression-protocol-for-embedded-systems)**<br/>http://github.com/BSeyfi/bicolor-image-compression-protocol-for-embedded-systems



- - -

**BICTES** stands for **B**itmap **I**mages **C**ompression **T**ool for **E**mbedded **S**ystems.
