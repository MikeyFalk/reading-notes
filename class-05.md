# Code 201 Reading Notes Day 5

## HTML

### Chapter 5: "Images" (pp. 94-125)

* HTML is used to add a picture to a webpage
* CSS can also be used
* images have several formats
* you will need to format an image to the right size
* you will need to optimize an image to make it load faster

* good practice to create a folder with images for the site
* large sites have multiple sub folders of images

`<img>` element to add an image to a site
`<src>` tells the browser where you can find the image
`<alt>`  provides the text description used if the site can't display the image or you can't see it reffered to as alt text, used by screen readers.
`<title>` - used to provide additional information about the image
`height` and `width` specify size but can be added in CSS but it is good practice to specify size so page can render and leave space
`<figure>` and `<figcaption>` - can be used to caption an image

* images can be placed before a paragraph - pararaph starts on a new row
* inside the start of a paragraph - first row aligns with bottom of image 
* in the middle of the paragraph - between word in the paragpraph 

* HTML5 doesn't use align this old code

#### always: 

* save image in the right format
* save images in the right size
* measure images in pixels

* JPEG good for many colors in an image
* GIF best for images with few colors or large areas of the same color

* important to save images at the size you want them to appear
* you can decrease image size but not increase image size without sacrificing quality.

* Best not to crop images instead add extra space to fit -like borders

### Chapter 11: "Color" (pp.246-263)

* How to spcify colors
* color terminology and contrast
* background color

* RGB - expressed in terms of how much red green and blue
* HEX Codes 6 digit codes
* Color Names - 147 predefined color names
* CSS3 has HSLA as well

`color` = tesxt color
`background-color` = background color for box
* need to specify since some browsers don't default to white users can set it

* CSS3 has an opacity available
* important to think about contrast for readability

* Hue Saturation Lightness and Alpha
* HSL and HSLA available in CSS3

### Chapter 12: "Text" (pp. 264-299)

Split into 2 groups
    1. affect font and its appearance
    2. affect on text no matter what the font you are using
* `font-family` specify typeface users need this type face installed on their computer, you can also specify a list of fonts for alternates
* `font-size` - size of font pixels or  precentages of default size (16px)
* `font-face` - used even if a user doesn't have it installed
* `font-weight` - bold
* `font-style` - italic
* `text-transform` - uppercase and lowercase
* `text-decoration` - underline and strike
* `line-height` - leading
* `letter-spacing` - `word-spacing` - self explanitory

[<-- Back](README.md)