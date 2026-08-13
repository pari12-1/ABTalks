# Teachable Machine Image Classification Experiment

## Objective

The task was to experiment with 2 or 3 class image classifier using Google's Teachable Machine and observe how the data changes when the quantity of data or noice is added.  

## Classes

- Phone
- Book

## Experiment 1 - Small Dataset

Training data:

- Phone: 8 images
- Book: 9 images

Test samples: 17

Correct predictions: 81%
Accuracy: 19%

## Experiment 2 - More Training Data

Training data:

- phone: 99 images
- Boots: 90 images
- pen: 82 images

Test samples: 271

Correct predictions: 100%

Accuracy: 100%

## Experiment 3 - Noisy / Inconsistent Data

- pen: 73 images
- book : 137

made the pen far away and close enough , shown open book . 

Test samples: 210

Correct predictions: 7%
wrong prediction : 93%
Accuracy: 7%

## Observations

1. More useful training examples improved the model's ability to
classify unseen inputs.

2. A varied dataset containing different angles, positions and
lighting conditions helped the model generalize better.

3. Incorrect labels and noisy samples reduced prediction quality and
made the classifier less reliable.

## Reflection

From this experiment, I observed that when I increased the amount of training data, the model started making more accurate and confident predictions. I also noticed that adding different angles, position and lighting conditions helped the model recognize objects better in new situations. On the other hand, noisy or incorrectly labelled data confused the model and reduced its prediction quality. This showed me that having more data is useful but the quality and variety of the data are just as important as the quantity. Overall, I learned that a model performs better when it is trained with enough clean, correctly labelled and diverse examples.