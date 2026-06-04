# mlops-git-assignment--Shini-Kim-

Course Code: MAI201
Date: June 4th, 2026

ML Ops Assignment
Name: Shini Kim
Student ID: skim597
Student #: 136080256

## Project Description

This project is to build and deploy an automated, restaurant recommendation engine using the
Yelp dataset filtered down for a particular location (this is to keep the scope simple for this
course given the limited time and resources).
The core MLOps infrastructure relies on an automated workflow pipeline that comfortably
handles raw data validation, model retraining, and containerized deployment by FastAPI. Finally,
the project integrates continuous monitoring to detect data drift in incoming reviews,
automatically triggering the pipeline to refresh and update the model as consumer food trends
change and evolve over

## Setup Instructions

We will set up a centralized feature store to manage dynamic user preferences and business attributes for low-latency, real-time inference.

## Prerequisites 

https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset

This Kaggle data source officially published by Yelp from 2021, provides very detailed,
feature-rich data. It has millions of user reviews, business attributes, and temporal check-in
data, providing high dimensional data needed for advanced feature engineering. This
complexity of the dataset allows us to simulate realistic production pipelines and track how
evolving consumer behaviors impact model perf
