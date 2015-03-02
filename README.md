This repository illustrates a bug in Chrome for Mac version 40.0.2214.115 (64-bit).

It displays three boxes, which have an SVG filter applied to them that converts them to greyscale.
Thus, the boxes will appear blue if the filter is not found and grey if it is not.

In a subdirectory, there is a CSS file, which refers to an SVG file in which the filters reside.

The first and last boxes should be grey, and the middle box should be blue.
However, the first box is blue and the other two are grey.
