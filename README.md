# Cosmetic Tweaks to Improve Fastpages

A carefully crafted `custom-styles.scss` to improve the look and feel of fastai/fastpages.

## Improvements

### Code and Output Styling

- Better code and output padding
- Cleaner code bordering and homogeneous border coloring
- Improved output styling

|Before|After|
|---|---|
|![](https://i.imgur.com/6OdYyAK.png)|![](https://i.imgur.com/GyybX1w.png)|


### Improved Post List Styling

Improved post listings with images and typographic balance:

|Before|After|
|---|---|
|![](https://i.imgur.com/u4TGU0W.png)|![](https://i.imgur.com/7kqYRI8.png)|

Fixed font size of `code` elements inside lists:

|Before|After|
|---|---|
|![](https://i.imgur.com/St7m9w0.png)|![](https://i.imgur.com/BPLFvsY.png)|

### Bug ~Fix~ Cover-up

Hides bug whereby graphviz (gv) generates a DOCTYPE that shows up in the generated post `"<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">"`:
 
|Before|After|
|---|---|
|![](https://i.imgur.com/OC9cgdE.png)|![](https://i.imgur.com/KdGS50q.png)|
 
## Installation

This file is meant to be a drop-in replacement for your `custom-styles.scss`. Simply drop the `custom-styles.scss` file in `./_sass/minima` (or incorporate it into your existing custom stylesheet).


