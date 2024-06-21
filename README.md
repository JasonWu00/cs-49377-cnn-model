# cs-49377-cnn-model
A project for the CSCI 49377 "Deep Learning" course to train a Convolutional Neural Network.

There is a README.md file in the "files" folder. It will discuss the organization structure of the various project stsge folders.

### Nature and Purpose of Project
This is a coursework project for the Deep Learning course mentioned above. Its goal is to build and train a classification model that can identify images as one of five categories.

The model is trained against the Pictures dataset. It is a set of 25,000 images divided into five categories: bell, dog, horse, house, tiger. The data set is proprietary and students were not permitted to redistribute it, therefore this repo does not contain a copy of it.

Student trained models are judged by their accuracy when ran against a special "Real World" holdout set of images. All models must achieve an F1-Macro score of 79% or greater in order to be considered.

### Project Stages and Procedures

This project is divided into a number of stages, each with corresponding work.
- Stage 1: The student compiles the Pictures dataset, which was received in the form of a zipped folder, into a number of TFDatasets files. The professors provided [a Google Colab notebook with sample code to use for completing this task](https://colab.research.google.com/drive/1xYVsV2e0W3t5gI67pvNTTsXNCCO4rQjR).
- Stage 2: The student generates a project proposal. In this proposal the student discusses what model architecture they plan to implement, what tests they plan to do to increase the model's performance, and other relevant details.
- Stage 3 and 4: The student runs the planned tests in their proposal or previous stage report, submits in-progress versions of their models to be graded, and writes stage reports on their experiments and results and next stage plans.
- Stage 5: The student submits a final version of their model, summarizes findings and conclusions in a final report, and presents a summary of this work to other students during the last two weeks of class time.