# KaggleLungCA

LUNA.ipynb contains code that takes the first subset, locates the nodules based on the annotations provided with the dataset, and extracts 3 slices (nodule center, and slice above and below it), as well as providing a mask for each slice with tissue directly surrounding it. Currently the mask selects area based on the diameter of the nodule provided in the annotations but it may be useful to use a set diameter (32x32 ?).
