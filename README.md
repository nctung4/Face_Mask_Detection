# Face Mask Detection
## Overview:
* It is a real-time face mask detection project, developed in python, using Deep Learning and OpenCV.
* I used the transfer learning technique. (MobileNetV2 architecture)
* Used several preprocessing technique, such as one-hot encoding the labels, or constructing the training image for data augmentation.
* The final model performs absolutely amazing, with almost a 100% accuracy.

## Final Model:
* MobileNetV2 architecture.
* Compiled with an adam optimizer, and binary crossentropy loss function.
* Added dropouts for regularizing the Neural Network.

## Model training plot:
![](https://github.com/nctung4/Face_Mask_Detection/blob/main/plot/model_training_plot.png "Model training plot")

## Model performance on new images:
![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/Mask1_resized.jpg "Mask 1") ![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/mask_2_pred_resized.jpg "Mask 1 prediction")
<br>
![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/Mask_2_resized.jpg "Mask 2") ![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/Mask2_pred_resized.jpg "Mask 2 prediction")
<br>
![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/No_Mask_1_resized.jpg "No Mask 1") ![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/No_Mask_1_pred_resized.jpg "No Mask 1 prediction")
<br>
![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/No_Mask_2_resized.jpg "No Mask 2") ![](https://github.com/nctung4/Face_Mask_Detection/blob/main/try_model_with_new_images/No_Mask_2_pred_resized.jpg "No Mask 2 prediction")
