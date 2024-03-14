
# Building the Eyes of a Self-Driving Car

In this project, I delve into the fascinating world of machine learning and its application in developing self-driving cars, focusing on the critical aspect of "vision" or semantic segmentation. Here's what I've accomplished:

* I researched and selected image segmentation datasets and pretrained models to understand the landscape and identify the best resources for our needs. 📖
* I fine-tuned an image segmentation model with new data, adjusting and optimizing it to improve accuracy and performance on specific outdoor scenes. 👾
* I developed a computer vision app that runs seamlessly on both mobile and desktop devices, enabling real-time semantic segmentation of outdoor scenes to distinguish roads, cars, pedestrians, and more. 📷
* I rigorously tested the segmentation model on both test datasets and real-world scenarios, measuring its performance and making necessary adjustments to enhance its reliability and efficiency. 📈

## Introduction

Self-driving cars are not just a technological marvel but also a potential life-saving innovation. To achieve full autonomy, these vehicles must possess an impeccable vision system powered by machine learning algorithms. As per [Tesla's insights](https://www.tesla.com/AI), semantic segmentation plays a pivotal role in this process by assigning a class to every pixel in an image, enabling a detailed understanding of the vehicle's surroundings.

Semantic segmentation represents a leap from traditional image classification. It does not just categorize an entire image but discerns and labels each pixel to map out different objects within a single frame. This technique is not only crucial for autonomous vehicles but also finds applications in medical imaging, among others. By the end of this journey, I have successfully built an application capable of performing semantic segmentation on outdoor scenes, effectively distinguishing between various elements like roads, cars, and pedestrians.

Here's a glimpse of the outcome:

![](https://i.ibb.co/RNv8MgQ/image.png)

## Step 0: Hugging Face Account Setup

## Step 1: Dataset Acquisition

## Step 2: Selecting a Pretrained Model

## Step 3: Model Fine-tuning
### 3a. Preprocessing and Metric Loading
### 3b. Overfitting a Subset with the Segformer Model
### 3c. Comprehensive Training on the Full Dataset
### 3d. Publishing the Model on the Hugging Face Hub

## Step 4: Performance Metrics Evaluation

## Step 5: Demo Development

## Step 6: Experimentation with a Zero-shot Image Segmentation Model

Throughout this project, I've been hands-on at every stage, from selecting datasets to fine-tuning models, and from developing a demo to evaluating performance metrics. This journey has not only been a testament to my technical abilities but also to my commitment to advancing autonomous vehicle technology.

