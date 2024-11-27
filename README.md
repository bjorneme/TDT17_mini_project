# 3D Head and Neck Tumor Segmentation (HNTS) using 3D Swin UNETR

### Introduction

This notebook segments head and neck tumors (HNTS). It uses 3D Swin UNETR architecture to perform segmentation of the 3D images. For improved performance pretrained weights and data augmentation is used to achieve better performance. Performance is measured using Dice Score. The project includes three different models:
- UNet
- SwinUNETR
- SwinUNETR using pretrained weights

### How to run the code

To run the code, it is necessary to execute it within IDUN. This is necessary to get access to the dataset. If the code is not run inside IDUN, the paths in the notebook must be adjusted to correct folders.

### Sources used:

[1]: Tang, Y., Yang, D., Li, W., Roth, H.R., Landman, B., Xu, D., Nath, V. and Hatamizadeh, A., 2022. Self-supervised pre-training of swin transformers for 3d medical image analysis. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 20730-20740).

[2]: Hatamizadeh, A., Nath, V., Tang, Y., Yang, D., Roth, H. and Xu, D., 2022. Swin UNETR: Swin Transformers for Semantic Segmentation of Brain Tumors in MRI Images. arXiv preprint arXiv:2201.01266.

[3] HNTS-MRG Challenge: Head and Neck Tumor Segmentation for MR-Guided Applications. https://www.hntschallenge.com/

[4] MONAI Framework: Medical Open Network for AI. https://monai.io/

[5] Cao, H., Wang, Y., Chen, J., Jiang, D., Zhang, X., Tian, Q., & Wang, M. (2022, October). Swin-unet: Unet-like pure transformer for medical image segmentation. In European conference on computer vision (pp. 205-218). Cham: Springer Nature Switzerland.

[6] MONAI Tutorials: https://github.com/Project-MONAI/tutorials/tree/main/3d_segmentation