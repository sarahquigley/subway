Subway
======

Relax and watch the trains go by.

View live version: [Go down to the subway.](https://subway.sarahquigley.net)

## What is Subway?

Subway is an experiment in CSS3 animations. Sit back and wait for a train (or two) to cross your browser window from left or right, lighting up the subway tunnel as they pass.

## How does it work?

### Layered Images

Absolute positioning is used to create a series of z-index ordered layers. From back to front, these layers consist of:
- Train background lighting effect, created using a linear gradient
- Back set of subway tunnel columns, a very simple repeated background image 
- Train, created using a series of images (as background images)
- Front set of subway columns, again, a simple repeated background image

This image layering creates the effect of a subway train travelling through a tunnel with columns lining either side. Columns are black, thus are invisible on the black background until the train and its background lighting appear.

### CSS3 animations

CSS3 animations are used to move the train across and off screen, from either the left or right.


## Did you create the artwork?

Yes, all the artwork is my own. It was created using Adobe Photoshop.


## Why did you make this?

I like to watch the subway trains go by. I also really like playing with CSS3 animations.


## Supported browsers 

Chrome, Firefox 5+, IE 10+, Opera 12+, Safari 4.0+.
