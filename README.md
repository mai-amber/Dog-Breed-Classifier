# Dog Breed Classifier

## Motivation
Determining whether a given image is a human or a dog isn't too big of a challenge, but then again determining which kind of dog you're looking at can be! That's precisely what this project aimed to solve.

## Project Definition
This project is the capstone of the Udacity data science nanodegree. The aim was to create a program that chooses a dog breed when shown a dog, and points to the most similar dog breed when shown a human.

## Repository files
The repository includes:

1. A Jupyter notebook of the project code which includes all the steps taken in coding the project plus questions and answers for further understanding of the material.
2. An HTML file of the project code which includes all the steps taken in coding the project plus questions and answers for further understanding of the material.
3. This README file

The second requirement of the project is a blog post, this is the link: 

https://maimon-amber.medium.com/is-it-a-dog-and-if-so-which-kind-a-cnn-classifier-can-help-you-decide-b997b8fbf941

## Analysis

The CNN from scratch achieved an accuracy of 6%. This means that only 6% of the dogs were correctly classified into the correct breed label. Only 5 percent above random chance.

Using the CNN from transfer learning achieved an accuracy of 37%. This means that only 37% of the dogs were correctly classified into the correct breed label. This is already 30+ percent above random chance, so we were starting to get somewhere with the predictions.

Using the CNN created using ResNet50 achieved an accuracy of 83%. This means that 83% of the dogs were correctly classified into the correct breed label. This is 80+ percent above random chance, and is a relatively good accuracy in breed prediction.

## Summary

This project started with EDA in which we imported datasets and detected humans and dogs. Next we created a CNN from scratch according to a provided hint model, which finally achieved an accuracy of 6 percent. Next we explored transfer learning in two ways, first using VGG16, ultimately attaining a 37% accuracy. Then using ResNet50, ultimately attaining an accuracy of 83%. In the end we used the ResNet50 model to construct an algorithm which differentiates between humans and dogs, and then provides a classification of dogs to their breeds and of humans to the dog breed which they most resemble.

## Conclusion

The classifier successfully achieves the objectives of the project and provides a solution to the problem of classifying dogs into breeds (and humans into breeds of most similarity)

## Acknowledgements
Thanks to Udacity for providing the structure of this project and the datasets, and to the reviewers for their detailed advice and comments.
