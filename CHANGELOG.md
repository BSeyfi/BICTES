# Changelog
All notable changes to this project will be documented in this file.
## [Unreleased]
### Add
- Improve protocol without violating protocol rules: make no if m<=2 (n=non blank, m=blank in a fragment)

## [1.0.1] - 2018-10-05
### Changed
- changed `const char` to `uint8_t` in output array for better support in embedded systems
- changed `int` to `uint16_t` in padding data for better support in embedded systems

## [1.0.0] - 2018-09-03
### Added
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
