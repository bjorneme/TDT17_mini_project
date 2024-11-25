# 3D Head and Neck Tumor Segmentation (HNTS) using 3D Swin UNETR

### Introduction

This notebook segments head and neck tumors (HNTS). It uses 3D Swin UNETR architecture to perform segmentation of the 3D images. For improved performance pretrained weights and data augmentation is used to achieve better performance. Performance is measured using Dice Score.

### Sources used:

[1]: Tang, Y., Yang, D., Li, W., Roth, H.R., Landman, B., Xu, D., Nath, V. and Hatamizadeh, A., 2022. Self-supervised pre-training of swin transformers for 3d medical image analysis. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 20730-20740).

[2]: Hatamizadeh, A., Nath, V., Tang, Y., Yang, D., Roth, H. and Xu, D., 2022. Swin UNETR: Swin Transformers for Semantic Segmentation of Brain Tumors in MRI Images. arXiv preprint arXiv:2201.01266.