# Encoding

using

# JavaScript



<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo" />
</div>


          


## Overview
To convert text data into an image and retrieving the same data from an image...



## Description
the main goal of this project is to encode text in image file and decode the image file in text file without any loss in data ...<br>
`txt` --> `image`  && `image` --> `txt`

## Process
Text file contains of data in form of word, this Words are made up of letter. Each letter occupied some byte of memory. Each letter has a unique ASCII value. ASCII is an 8-bit code. That is, it uses eight bits to represent a letter.

So for each letter there is an ASCII value and each ASCII value is 8 bit.

Now image is made up of pixels and every bit data is represented in `0` or `1`
If we represent `0` as `WHITE` and `1` as `BLACK`

So we can fill each pixel with `BLACK` or `WHITE`<br>
So 8 Pixel will correspond to a ASCII number of a letter.

### Problem
Problem with this approach is <br>
8 pixel correspond to a letter and each pixel is made up of `RGB` where is color is 8bit (0-255), so a pixel is `RGB` `8×3=24 bit`. So even of we use black and white the size is increased by 3 times per pixel,and we are using 8 pixel to correspond a letter so in total it is increased by 8×24=192 times

<br>

Letter size= `8bit`     <br>
pixel = `8×3`= `24 bit`     <br>
no of pixel to represent a letter = `8`     <br>
total no of bit for a letter= `8×24` = `192 bit`     <br>
Size of letters increased by `24 times` 






---

## Encode

Step 1.
> `Upload` the .txt file 

Step 2.
>click `encode`

Step 3.
>click `Download`

> [!NOTE]
>The text file should be in  `.txt` format


___

## Decode

Step 1.
> `Upload` the image file 

Step 2.
>click `decode`

Step 3.
>click `Download`


> [!NOTE]
>The image file should be in `.png` format

___

## published at:
[/Encoder](https://imposter404.github.io/Encoder)