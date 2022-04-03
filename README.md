# Covid-Detection-using-CNN
Detecting COVID using four different CNN algorithms - Xception, VGG19, ResNet50, InceptionV3. 

**Introduction**

Novel coronavirus pandemic hit the globe in December 2019. The virus has caused millions of deaths all over the globe. This has caused tremendous pressure on the healthcare system and social lives. Thus, the need to detect COVID at an early stage and also at a faster rate will help us fight against the virus. One of the primary reasons for the rapid spreading of the disease is not having the testing kits and also the time it takes to provide the result. Hence, using imaging techniques like chest X-rays will detect the virus quickly and effectively as lungs are affected when a person comes in contact with the virus. In our work, we used chest X-rays to detect COVID-19 as they are more affordable and available in every clinic. We have used the convolutional neural network (CNN) algorithm to predict the virus. We analyzed four different models, determined the results, confusion matrices, and accuracy of all models. The Xception model gave out the best accuracy with 93%. 

**Dataset Description**

For testing the results of our models, we have used chest X-rays of patients who have COVID and who are healthy. We have gathered the dataset from the GitHub open repository. Our dataset has a complete total of 940 images of chest X-rays. Out of these images, 505 chest X-rays are of healthy patients and 435 chest X-rays are of COVID19 affected patients. 80% of the data is used for training the model and 20% for testing the model. All the images are in different dimensions, so we resized them to 224 x 224 and are normalized. 

**Conclusion**

COVID-19 is burgeoning very quickly. In this work, we have analyzed four CNN models to classify people who are affected with COVID-19 using their chest X-rays. Our Xception model achieved the best accuracy with 93%. VGG19 & ResNet50 models achieved an accuracy of 91%. The InceptionV3 model achieved an accuracy of 89%. We finally classified COVID-19 scans, and it shows possible scope for the future to automate diagnosis tasks.  
