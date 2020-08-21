# The Effects of Skin Lesion Segmentation on the Dermoscopic Image Classification Performance
This repository contains the derived classification probability vectors (from both sets of experiments) and also automatically created segmentation masks (SkinUNet, SkinFPN+, and SkinLinkNet) that were used in our study. The classification probability vectors and the segmentation masks can be found in the respective folders. 
![Project Image](https://github.com/masih4/Skin-lesion-segmentation-effects-of-the-classification-perfromnce/blob/master/Project.jpg)

## Files description:
- image_ids.pdf: Contains two tables. The first table shows the image IDs (from the ISIC 2017 test set) of the images that were only classified correctly when the reference dataset was used but were incorrectly classified when the dilated cropped dataset was used. The second table shows the image IDs (from the ISIC 2017 test set) of the images that were only classified correctly when the dilated cropped dataset was used but were incorrectly classified when the reference dataset was used.

- predictions.zip: contains predictions for both sets of experiments. The classification prediction vectors for the first set of experiments are inside the "manual segmentation" folder, the classification prediction vectors for the second set of experiments are inside the "automatic segmentation" folder and the classification prediction vectors for the reference dataset is inside the "reference" folder.
- Segmentation_masks.zip: contains the automatically created segmentation masks for all 600 test images. These segementation masks were used in the second set of experiments.

## Useful links to perform statistical tests:
- https://www.medcalc.org/manual/comparison_of_roc_curves.php (for AUC comparison)
- https://ch.mathworks.com/help/stats/testcholdout.html (for McNemar statistical test)
- https://ch.mathworks.com/help/stats/signrank.html (for Wilcoxon signed-rank test method)


## References
```
@article{Mahbod2020,
title = "The Effects of Skin Lesion Segmentation on the Dermoscopic Image Classification Performance",
author="Mahbod, Amirreza and Tschandl, Philipp and Langs, Georg  and Ecker, Rupert and Ellinger, Isabella",
year="2020",
publisher="",
pages = "",
abstract="",
doi=""
}
```
