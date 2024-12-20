# Predict Model - Sentiment Analysis for Movies (IBM) 🚀

Welcome to the **Predict Model** project! This project provides a machine learning model for **sentiment analysis** on movie reviews, determining whether the sentiment is **positive** or **negative**. The model is packaged in a **Docker container** for easy deployment and predictions.

## Description 📖

This project uses a **predictive model** designed for **sentiment analysis** on **IBM movie reviews**. The model analyzes text input and predicts whether the sentiment behind the movie review is positive or negative. It is packaged using **Docker** to make it easy to run in different environments without worrying about dependencies or system configurations.

The model is deployed via a Docker container and exposes an **API** on port **8000**, allowing users to send movie review text and receive sentiment predictions.

## Features ✨

- Dockerized sentiment analysis model for easy deployment 🚢
- Predicts if movie reviews are **positive** or **negative** based on the text input 🎥
- API endpoint for making predictions 📡
- Exposed port: **8000** (can be configured)
- Supports both local and cloud deployments ☁️

## How to Use 🛠️

Follow these steps to get the application running on your local machine:

### Prerequisites ⚙️

1. **Docker** must be installed on your system. You can install Docker by following the official installation guide here: [Docker Installation](https://docs.docker.com/get-docker/)

### Pull the Docker Image 📥

You can pull the latest Docker image of the project from Docker Hub:

```bash

docker pull ayaalhamwe/predict_model:latest
```
### Run the Docker Container 🏃‍♂️

After pulling the image, you can run the container with the following command

```bash
docker run -d -p 8000:8000 ayaalhamwe/predict_model:latest
```
### Test the Sentiment Analysis API 🌐
Once the container is up and running, you can test the sentiment analysis API by sending a POST request to:

```bash
http://localhost:8000/predict
```
### Docker Image Information 🐳

- **Image Name**: ayaalhamwe/predict_model
- **Tag**: latest
- **Docker Hub URL**: [Docker Hub Repository](https://hub.docker.com/r/ayaalhamwe/predict_model)
