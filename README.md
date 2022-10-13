# Building-the-Eyes-of-a-Self-Driving-Car

Specifically, I will cover:

* finding image segmentation datasets and pretrained models 📖
* fine-tuning an image segmentation model on new data 👾
* building a computer vision app you can run on your phone or laptop 📷
* measuring the performance of a segmentation model on test data and the real world 📈

# Introduction
Self-driving cars are an exciting real-world application of machine learning, with the potential to save many lives each year. In order for self-driving cars to be fully autonomous, they need to "see" and "understand" the world around them. What are the machine learning algorithms that enable this? Let's take a look at [Tesla's website](https://www.tesla.com/AI): "Our per-camera networks analyze raws images to perform **semantic segmentation**..."

What is semantic segmentation? Semantic segmentation is the process of assigning a class to *every pixel in an image*. Image classification, which assigns a class to the entire image. Semantic segmentation is a more fine-grained version, which recognizes that an image can be made up of different objects: for example, an image taken by a camera on a self-driving car could consist of pedestrians, trees, and other cars. Semantic segmentation is used in many other applications as well, such as medical machine learning, where it can be used to identify organs in radiological images. Rather than assigning a single label to the entire image, a semantic segmentation model assigns each pixel a category so that we understand both *what* an image is, and *where* it is. 

By the end of this project, you'll have built an app that you can run on your laptop or phone that performs semantic segmentation on pictures of the outdoors scenes and will identify the road from the cars from the pedestrians, and so on. It will look something like this:

![](https://i.ibb.co/RNv8MgQ/image.png)

# Step 0: Log In to Hugging Face

# Step 1: Loading a Dataset

# Step 2: Loading a Pretrained Model

# Step 3: Fine-tuning Your Model on the Dataset
3a. Preprocess the Dataset and Load the Metric
3b. Fine-Tune the Segformer Model on a Training Subset (and Overfit)
3c. Fine-Tune the Segformer Model on the Entire Training Set
3d. Upload your model to the Hugging Face Hub!

# Step 4: Reporting Model Metrics

# Step 5: Building a Demo

# Step 6: Try a zero-shot image segmentation model.
