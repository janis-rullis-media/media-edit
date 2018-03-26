# How to extract a contour from an object?

![The original picture](../How-to-extract-an-object/images/extracted-object.png)

## 1. Reduce colors to only  black and white

Image -> Mode -> Indexed ...

Select 'Use black and white (1-bit) palette.

Click 'OK'.

![Indexed colors](images/indexed-colors.png)

![B & W](images/bw.png)

## 2. Create a border around the object

Select outside the object with the 'Fuzzy Select Tool'.

Select -> Invert.

Select -> Grow.

Select how thick the contour should be.

![grow-selection](images/grow-selection.png)

## 3. Color the contour white with the 'Bucket Fill'

![Increased selection](images/increased-selection.png)

![White contour](images/white-contour.png)

## 4. Remove the black color

Switch the image's mode from 'Indexed' back to 'RGB'.

Image -> Mode -> RGB.

Replace the black color with transparency (alpha).

Color -> Color to alpha.

![Color to alpha](images/color-to-alpha.png)

![Contour](images/contour.png)

