# Face-mask-detection-using-Ternsoflow
 Researched a lot about the models which have good advantage to use of  and started doing with Convolutional Neural Network. But  there is lot of inaccuracy  which makes us to use mobile net .So Ichanged our idea of using Cnn to Inception V5 which has a good accuracy with the dataset  had.so  Fixed to use the Inception Model.

For Face Detection ,There are Haar cascades and Mtcnn and Dsfd and many more I have used Haar cascade and mtcnn at the same time to make it more accurate but all the problem I faced is with the face detection since the key features are missing due to the mask .Dsfd (Dual shot face detector) in which we have to use pytorch so we don’t want to make it too complicate and so decided as to discard it.
So  Final is Inception Model with MTCNN and Haar Cascades.
At First I had designed our mode with taking the faces alone by cropping only faces and training them but later  have feel to change the model to inceptionv3 so  changed accordingly
I have used pretrained model with imagenet weights and the accuracy is being very good as 94% of testing data
I feel MTCNN and HAAR CASCADE is not that accurate always but again its good for face detection if it does not have mask on

