# 3D Brain MRI Registration using ITK-elastix

This is part of the Medical Image Registration and Applications Course

This project provides an image registration pipeline for medical images (Brain MRI) using the ITK-elastix framework. The pipeline includes rigid and non-rigid (B-spline) transformations, label transformation, and visualization of registration results

Image registration aligns a moving image to a fixed reference image, enabling comparisons or combining multimodal data. This pipeline utilizes ITK-elastix, a robust library for image registration, supporting rigid, affine, and deformable transformations.

This pipeline leverages ITK-elastix for robust image registration.

Key features:
Rigid registration: Aligns images using rotation and translation.
B-spline registration: Allows complex deformations for better alignment.
Label transformation: Applies registration parameters to segmentation labels.
Visualization: Middle slices of the fixed, moving, and registered images.