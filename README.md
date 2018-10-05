![](https://user-images.githubusercontent.com/42473071/44986714-f7f9cb00-af99-11e8-9649-ee6b439432cd.png)
# BICTES
**BICTES** is a tool to compress 1-bit bitmap images for use in embedded systems. ( jpg, png and bmp files, colorful, grayscale  image or 1-bit bitmap can be used as an input image)

- - - -

Memory and also computing power in embedded systems are in tight conditions so it is a need to make images as small as we can but simple to decompress. BICTES do this job.
BICTES creates an array of `uint8_t` (replaceable with `char`) for use in `C` or C-like languages.

**BITSEC** is designed to make data array from image to use in embedded systems on black and white LCD displays.
<br/>

![bictes-sample](https://user-images.githubusercontent.com/42473071/46546087-fd1da300-c8d4-11e8-83bf-7c8335c1b963.png)

- [Installation](#installation)
- [Features](#features)
- [Changelog](#changelog)
- [License](#license)
- [Acknowledgment](#acknowledgment)

## Installation
Download `BICTES.exe` from `Release` page:https://github.com/BSeyfi/BICTES/releases<br/>
**Requirements:** `.Net Framework 4.0` or later installed on windows system.

## Features
- Convert RGB or grayscale image to 1-bit monochrome image (support jpg, png and bmp files) and display converted image
- Save the converted image in the monochrome format
- Convert monochrome image to C Array and copy
- Convert monochrome image to compressed array due to [bicolor image compression protocol for embedded systems](https://github.com/BSeyfi/bicolor-image-compression-protocol-for-embedded-systems) and copy
- Copy compressed image array with padding
- Recreate image from the compressed array to verify the compressed array
- Extract count of fully black and fully white chunks
- Extract padding data
- Extract the width, height, and offset of the first chunk
- Calculate the size of the uncompressed array
- Calculate the size of the compressed array
- Calculate compression ratio
- Add blank row(s) to make image height divisible by eight

## Changelog
All notable changes to this project will be documented in [CHANGELOG.md](https://github.com/BSeyfi/BICTES/blob/master/CHANGELOG.md) file.


## License
This software is provided as Freeware for private non-commercial or educational use, including non-profit organization.
COPYRIGHT (c) 2018 Behzad Seyfi, All rights reserved
## Acknowledgment
-  **bicolor image compression protocol for embedded systems: http://github.com/BSeyfi/bicolor-image-compression-protocol-for-embedded-systems**



- - -

**BICTES** stands for **B**itmap **I**mages **C**ompression **T**ool for **E**mbedded **S**ystems.
