# Extended Mask RCNN

1. Unet.ipynb consists of the code that gives you the segmented image.

2. Unet basically takes the given test image and converts it into the corresponding
predicted segmented image.

3. We have saved the weights that we had obtained after training our Unet model. The
trained weights are also uploaded on our github.

4. Dataset is in the folder given on our github. (The link to our github repo is in the
presentation slides.)

5. You need to take extra care while loading the model.

6. Classifier_traini - Model is defined and trained on our dataset and we have saved the
weights of the model for future use, which is there in the weights folder on github.

7. Classifier_predict - it loads the earlier saved model and predicts the yoga pose class.
The yoga dataset we have used is taken from: https://www.amarchenkova.com/
But having said that we have tested it on our images. Test images used are uploaded in yoga_set/test.

8. The Unet model architecture is taken from: https://arxiv.org/abs/1505.04597

9. This repo was used as reference:
https://github.com/IntelAI/unet
https://github.com/karolzak/keras-unet
https://github.com/sevakon/unet-keras

10. Rest of the work completely belongs to us.

11. Link for video:
https://drive.google.com/drive/folders/1nsjqpkxt6bbU8ALpJY4q12oQAXVpnire?usp=s
haring

12. Link for Github: https://github.com/atharva417/Yoga_Pose_GNR638

13. Link for downloading model weights: https://drive.google.com/drive/folders/1wXgT761NnPnn8k0p35e8uIbUXkx5d9nH?usp=sharing

Some precautions that are to be taken while training on unet model:
a. Dataset must always have two different folders, test and train.
b. The test folder must contain all images in .png format and named as 0.png and so
on.
c. The train folder must contain three folders aug, image and label.
d. Image and label both should contain images in .png format and named as 0.png and
so on.
e. We have added an extra data_aug.ipynb file which will augment the given masks and
images and save them in the aug folder.\
