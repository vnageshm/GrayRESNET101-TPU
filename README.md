# GrayRESNET101-TPU
This repository contains the modified code to pretrain ResNet101 architecture on the entire ImageNet dataset using grayscale images only.
The idea behind pretraining ResNet101 using only grayscale images is that it will be helpful for medical images. <br/>
Any deep learning model applied to medical images can use this code to obtain a pretrained ResNet101 model for efficient and better feature extraction as proposed by this paper: [Pre-Training on grayscale ImageNet improves medical image classification](http://openaccess.thecvf.com/content_ECCVW_2018/papers/11134/Xie_Pre-training_on_Grayscale_ImageNet_Improves_Medical_Image_Classification_ECCVW_2018_paper.pdf)
<br/>
**The entire procedure to enable TPUs and start the training is provided here [Google Cloud: Pretrain ResNet101](https://cloud.google.com/tpu/docs/tutorials/resnet).** Once the VM has been setup according to the procedure above, the 4 codes above can be replaced in the folders on the cloud and training can be started. The requisite grayscale trained ResNet101 will then be stored in Google Storage of the account holder.

