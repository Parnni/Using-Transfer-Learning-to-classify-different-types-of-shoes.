# Project - Using Transfer Learning to classify different types of shoes.

## Table of Contents
- [Overview](#Overview)
- [Problem Statement](#Problem-Statement)
- [Methodology](#Methodology)
- [Technologies Used](#Technologies-Used)
- [Results](#Result)

## Overview
E-commerce has rapidly grown and their business strategies are completely based on user actions and user experiences. Although it is completely based on users, we should also not forget to say that there is a technology bridge in between users and growth in business. It may be Machine Learning or Deep Learning. Companies apply many image classification techniques on data to improve their catalog and give best suggestions to the users. They need accurate product classification on their platforms for better user experience.

## Problem Statement
Given the images of a product with multiple categories, train a model which can classify the type of a product. Data is all about images of shoes with multiple categories and data is collected from a popular Ecommerce site. Data set consists of two folders train and test. Train set consists of images belonging to 3 different categories of shoes in 3 different folders: Boots, Sandals and Slippers. Test set consists of images belonging to all 3 categories of shoes into a single folder.

## Methodology
- Used Image Data Generator to get the data from the folders.
- Used Transfer Learning (VGG16) for classification.

## Technologies Used
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Results
Training accuary is: 0.9981<br>
Validation accuary is: 0.9911
