# Indian Sign Language Recognition

> Academic / Foundation Project

A computer-vision project that recognizes Indian Sign Language alphabet gestures from images and translates the predicted sign into readable text for text-to-speech output.

## Problem

People who communicate using sign language can face a communication barrier when others do not understand the gesture. This project explores an accessible bridge: image-based sign recognition followed by text and speech conversion.

## Approach

- Built an alphabet-level image classification workflow for Indian Sign Language gestures.
- Used image samples captured under different lighting conditions and hand orientations.
- Applied transfer learning with the InceptionV3 convolutional neural network through TensorFlow.
- Used OpenCV for image processing and Python for data preparation, model training, and inference.
- Mapped the predicted alphabet to text, designed for downstream text-to-speech synthesis.

## System Flow

`Gesture image → Image preprocessing → InceptionV3 classifier → Predicted alphabet → Text → Speech output`

## Technology

`Python` `OpenCV` `TensorFlow` `InceptionV3` `NumPy` `Pandas` `Text to Speech`

## Project Material

The accompanying project report documents the problem statement, system design, dataset structure, model approach, testing, and future scope.

---

Built during my bachelor's program as an academic project.
