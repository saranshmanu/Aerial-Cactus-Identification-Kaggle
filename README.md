# Aerial Cactus Identification
## Determine whether an image contains a columnar cactus

To assess the impact of climate change on Earth's flora and fauna, it is vital to quantify how human activities such as logging, mining, and agriculture are impacting our protected natural areas. Researchers in Mexico have created the VIGIA project, which aims to build a system for autonomous surveillance of protected areas. A first step in such an effort is the ability to recognize the vegetation inside the protected areas. In this competition, you are tasked with creation of an algorithm that can identify a specific type of cactus in aerial imagery.

### Objective

In the competition we had created a CNN model using Pytorch to classify the images samples in which there is a higher chances of finding a cactus plant from the images which did not have any cactus.

<center><img src = "dataset/readme.jpg"></center>

### Result

We obtained good accuracy of 99.78% on the test set after training the model for 40 epochs. There were a total of 4000 images in which we had to find the images which contained cactus plants and the trained deep learning model was used for the prediction.

## Frameworks

<ul>
    <li>Pandas
    <li>Numpy
    <li>Pytorch
    <li>Torchvision
</ul>

## Resources

<ul>
    <li><a href = "https://www.kaggle.com/c/aerial-cactus-identification/overview">Kaggle Competition</a>
</ul>
