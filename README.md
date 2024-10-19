# EAI_BCI_Sapienza

## Introduction
This repository contains the code for the final project of the course "Elective in AI" at Sapienza University of Rome.
The project consists in the assessment of the performance of different machine learning models on a proprietary dataset of EEG signals.
Methods used in this project are:
Specialized models to classify signals for each subset of class belonging to a specific task from the dataset. These models aim to capture task-specific features and optimize classification performance for individual tasks.
A more generalist model designed to handle multiple tasks simultaneously. By incorporating a broader range of features and leveraging shared information across tasks, this model offers flexibility and scalability in BCI applications.
A meta-learning approach based on the Prototypical Network architecture.
Contrastive learning to train an auto encoder used to observe the behavior of the generalist model and the meta learning approach.
Through rigorous experimentation and evaluation, we seek to compare the performance of these architectures and demonstrate their efficacy in EEG signal classification tasks.

## Dataset
You can download the dataset from the following link: [Dataset](https://drive.google.com/file/d/1DwVVUFQJr6wjOHeqEMOYnYfEaFUQmXk_/view?usp=drive_link)

## Code
The three files that contain the code are:
7_4.ipynb
7_5.ipynb
7_6.ipynb
