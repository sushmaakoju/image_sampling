# image_sampling


## Resample given source image at Ground Sampling Distance D_s to target Ground Sampling Distance D_t.
#### The scripts resample_gsd_utah and resample_gsd_utah_without_image_output are to resample images : given a set of aerial images for a Ground Sampling Distance D_s, resample these images to GSD D_target.
* Example Ground sampling distance : 12.5cm/px and target Ground sampling distance: 15cm/px, 20.0.cm/px and 30.0cm/px.
* Besides each of the source images for distance D (eg: 12.5cm/px), there are also location annotations with labels. The scripts rescales annotations to target Ground Sampling Distance (eg: 15cm/px, 20cm/px and 30cm/px respectively).
* Lastly this script validates and displays each image, annotation file pair for compairson between source images with GSD 12.5cm/px with that each of target image, annotation file pair for Ground Sampling distance(15cm/px, 20cm/px and 30cm/px).
* Validation also involves displaying example cropped images from given annotation location (Bounding box) to compare how the resulting resampled images with rescaled annotations differs with that of source GSD (Source GSD 12.5cm/px to any of target GSD : 15cm/px, 20cm/px and 30cm/px).

* following two scripts are examples of resampling.
    * [To see resampling images to Target Ground sampling distance, click here:](https://nbviewer.jupyter.org/github/sushmaakoju/image_sampling/blob/main/src/notebooks/resample_gsd_utah.ipynb)

    * [To see resampling images to Target Ground sampling distance without any outputs displayed inline, click here:](https://nbviewer.jupyter.org/github/sushmaakoju/image_sampling/blob/main/src/notebooks/resample_gsd_utah_without_image_output.ipynb)