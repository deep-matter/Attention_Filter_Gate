# Attention Filter Gate

Welcome to the Attention Filter Gate repository! Here, we provide an implementation of our proposed method, the Attention Filter, which is based on the Fast Fourier Transform. In the accompanying PDF document, we explain in detail the steps we have taken to tackle the problem at hand.

### Dataset Description

The data used in this project is hosted by a competition on the Kaggle platform, namely the Left Atrial Segmentation Challenge. We have used medical images of the left atrium, which are in 3D and come with 30 corresponding masks.

* Data Source :
The Data we have been used is Host in Kaggle Platform competiotion , to download Run following command :
there're few step needed to be consider before running the Script 
    * First :</br>
        Create an account in Kaggle and Get API Token 
    * Second :</br>
        Replace your Kaggle API Tokon which stored in **kaggle.json** in the right path in Script to have authrozation
            ```sh
                 chmod a+x download.sh && ./download.sh
            ```

### Introduction

In this project, we aim to build a new mechanism, the Attention Filter Gate, which will address the weaknesses of previous approaches used to handle certain problems, such as:
- **Critical Problems we assign ** 

    * Losing features during extraction when using deep segmentation models
    * Handling data with higher resolutions
    * Reducing time complexity of training
    * Reducing energy consumption during training
    * Learning from spatial domain

Through our exploration of these weaknesses, we aim to provide a better solution to these problems using our proposed Attention Filter Gate mechanism.
