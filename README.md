# Rotate Your Photos!
Create recursive image transformation animations

## Demo

## Usage Instructions

An animation can be generated using the `rotate.py` or `transform.py` file.

## rotate&#46;py

## Arguments:

`python3.7 rotate.py <input_image.png> <output_file.mp4>`

## transform&#46;py

## Arguments:

`python3.7 transform.py <input_image.png> <output_file.mp4> optional: <transform_type>`

## Transformation Types

0: rotation

1: vertical flip

2: horizontal flip

3: vertical+horizontal flip

## Others

Valid output formats include .m4a .mp4 .mov .avi

The image needs to have NxN dimensions where N is a power of 2. If these requirements are not met, the program can automatically resize the image to the closest power of 2.
