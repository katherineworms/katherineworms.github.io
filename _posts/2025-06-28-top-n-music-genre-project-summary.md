---
title: "Project Summary: Top-N Music Genre Classification Neural Network"
excerpt_separator: "<!--more-->"
categories:
  - Projects
tags:
  - Project Summary
  - Machine Learning
  - Neural Networks
  - Python
  - TensorFlow
  - Keras
  - Artifical Intelligence
classes: wide
---

Project Overview: The Top-N Music Genre Classification Neural Network is a web application that uses a convolutional neural network to analyze audio files or YouTube links and predict the most likely music genres \
Link to Repository: https://github.com/katherineworms/music-genre-nn \
Languages/Tools Used: Python, Flask, TensorFlow, Keras, HTML/CSS, Plotly.js, Docker, Google Cloud Platform \

Introduction: 
The Top-N Music Genre Classification Neural Network is a web application designed to classify audio files or YouTube audio streams into their most likely music genres using a convolutional neural network (CNN). By analyzing audio data, the model predicts the top genres, allowing users to explore machine learning applications in sound analysis. This project demonstrates the integration of backend machine learning with a user-friendly frontend interface and cloud deployment.

Demonstration: 
Users can interact with the application by uploading audio files in .wav, .au, or .ogg formats or by submitting a YouTube link. The uploaded audio is processed, and the application displays the top predicted genres based on the trained CNN model. The results provide a quick and intuitive way to understand audio classification in real-time.

Key Features:
* Upload local audio files (.wav, .au, .ogg) up to 100 MB
* Submit YouTube URLs for automatic audio extraction and classification
* Display the top predicted genres from a trained CNN
* Interactive web interface using HTML templates and Plotly.js visualizations

Tech Stack:
* Backend: Python, Flask
* Frontend: HTML (Jinja2), CSS, Plotly.js
* Machine Learning: TensorFlow, Keras
* Storage & Deployment: Google Cloud Storage, Docker, Google Cloud Run
* Other Tools: yt-dlp for YouTube extraction, Playwright for cookie management, dotenv for environment configuration

Environment & Data Setup:
The project provides instructions for setting up a Python virtual environment, installing required libraries, downloading raw and processed GTZAN dataset files, and loading a pre-trained CNN model for inference. Users can run the application locally with Flask or deploy it using Docker to Google Cloud Platform.

Future Improvements:
Planned enhancements include adding a progress bar for long YouTube processing, improving model accuracy, and enabling user login to save classification results.

Contributors:

Samantha Evans – evanss4@oregonstate.edu

Miguel Fernandez – fernandezm0115@gmail.com

Katherine Worms – wormsk@oregonstate.edu




