

# Dog breed classification

### Introduction
This project is part of the Udacity Data Scentist Nanodegree and involves the implementation of algorithms for a dog identification app.

### Motivation

The World Canine Organization (FCI) is currently listing more than 300 officially recognised dog breeds. Over thousands of years, mankind has managed to create an impressive diversity of canine phenotypes and an almost uncanny range of physical and behavioural characteristics of their faithful four-legged friends. However, apart from cynology scholars, dog breeders and some proven dog lovers most people shrug their shoulders in a clueless gesture, when asked to name the breed of a randomly presented dog, at least when it is not exactly a representative of one of the most popular and well known breeds like Dachshund, German Shepard or pug. If you are one of the few people who finds it slightly embarrassing not being able to identify dogs like a cynologist, you are probably pleased to learn that there might be a technical solution. Because thankfully, the aspiring and astonishing field of Deep Learning and artificial neural networks provides powerful concepts and methods for addressing this sort of classification tasks.
In this project we will develop ideas for a dog identification app using deep learning concepts. The software is intended to accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog’s breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
Our project involves the following steps:
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dogs
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 6: Write your Algorithm
- Step 7: Test Your Algorithm

### Medium blog post

Link to the corresponding [blog post on Medium](https://medium.com/@normannexo/dog-breed-classification-using-deep-learning-concepts-23213d67936c).

### Files

- `dog_app.ipynb`  - A jupyter notebook with the main code
-  `dog_app.html`  - the html version of the jupyter notebook
-  `extract_bottleneck_features.py`  - helper functions to extract bottleneck features from models
-  `images/`  - folder with example images
-  `haarcascades/`  - haar cascade definition file for face recognition
-  `requirements/`  - requirements files

### Used libraries

- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`
- `cv2`

### Conclusion

In this project we developed several approaches for the development of an app for the identification of dog breeds, and we achieved our best results with the application of a transfer learning model. We achieved an accuracy of 83% in our tests.  We also learned how to build convolution networks from scratch, which was a very educational undertaking, even though we soon realized that there are significantly more promising methods, particularly with the application of transfer learning.  

However, we still see several options to further improve our algorithm in the future:

- We could gather more training data.
- We could employ data augmentation to prevent overfitting.
- We could add more layers to make our model more complex and hopefully more powerful.
- We could extend our training time and add more epochs to the training.

But all in all, the accuracy levels from our tests, along with the tests with specific sample images, suggest that we already have a serious model we could work with in a real app.


### Acknowledgements

Major parts of the source code are based on the original repository by Udacity: https://github.com/udacity/dog-project
