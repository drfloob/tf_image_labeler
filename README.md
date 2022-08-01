This simple tool helps you label images for Tensorflow Lite's Object Detection library.

Run: `tf_labeler image -l <custom_label> -p /path/to/training_image.jpg`

Usage:

1. select the area you would like to label
2. click the "Accept" button (the checkmark)

The generated CSV line will be copied to your clipboard. Something like:

```
$ tf_labeler image -l arst -p /home/me/proj/test_images/maxresdefault.jpg
UNASSIGNED,/home/me/proj/test_images/maxresdefault.jpg,arst,0.728125,0.259722,,,0.948438,0.475
```

![image](https://raw.githubusercontent.com/drfloob/tf_image_labeler/tf-image-labeler/data/img/preview/animatedUsage.gif)

Forked from flameshot-org/flameshot