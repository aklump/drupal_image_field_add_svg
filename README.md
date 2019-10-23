# Image Field Add SVG

## About

Drupal 7's core image field does not allow you to upload svg files.   This module takes care of that.  Simply enable and proceed; now you may add .svg as a valid image file extension.

## Strategy

1. This module uses hooks to alter the core behavior of the image field module.
2. By enabling it you will be able to add the `.svg` extension as a valid image file type to any image field.
3. Also, svg files will appear in the `<img>` tags.

## Image Styles

Unless an effect appears in this list, the svg file will ignore any image effects or styles attached to it:

- `image_scale_effect`

## No Drupal 8

There is a [contrib module](https://www.drupal.org/project/svg_image) for that.
