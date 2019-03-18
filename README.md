# Landmark-Recognition-with-Keras

## Time to tell a story...
Well, I m finishing my master degree in Artificial Inteligent in the "Universidad Politecnica de Madrid" 
[MUIA](http://www.dia.fi.upm.es/masteria/?q=es/MUIA) and i will present this Neural Network as my final proyect in June.
I have always liked robots, and in the master degree i had a robots assignature where i had a project 
with visual landmarks, classifying photos with a K-NN. 
As i am living in a student residence while i study in Madrid i thought 
"Ey Amable, why don't you take photos from the residence and train a CNN to 
identify every important point of the residence? It could be fun! It's like the robot assignature project" 
I proposed it to one of my teachers and that is how i have end up doing this proyect.

## The Neural Network
73% accuracy

Every day better.

![Confusion matrix](https://github.com/Amable-Valdes/Landmark-Recognition-with-Keras/blob/master/others/confusionMatrixWithNorm.PNG)

The confusion matrix seens good; now we only have little fails on node 4 and 6, but nothing important.

In the past i had 200x130 images, after that 96x54 and now i have decided to work with 128x72 images.
I think this will be the final dimensions of the images.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

You have the data folder, where there are all the images i used to train the Neural Network, and you have 2 
Neural Network Jupyter Notebooks: one to test the Neural Network on Google Colab and other 
to test the Neural Network on your own computer desktop (Keras and TensorFlow needed).

Also, you have a .h5 file with the last CNN trained. You can load it with Keras.

In the "dynamic_tests" folder you can watch the videos where i show the Neural Network working.

If you read any bad translation in documentation or code send me an email with the correct sentences (^.^)

Thanks for read me!