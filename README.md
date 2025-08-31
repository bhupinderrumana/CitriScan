#CitriScan 🌿

An AI-powered web application for the early detection of citrus leaf diseases using deep learning, promoting sustainable agricultural practices.

Overview
Citrus Canker is a major disease affecting citrus crops in India, leading to significant economic losses and increased chemical usage. This project, CitriScan, aims to address this problem by providing an accessible and accurate tool for the early detection of citrus leaf diseases. By leveraging deep learning, this application empowers farmers to move from broad, preventative spraying to targeted, timely interventions, thus supporting more sustainable and profitable agriculture.

The project involves a comparative analysis ("bake-off") of different Convolutional Neural Network (CNN) architectures to find the most effective model for the task. The best-performing model is then integrated into a user-friendly web application built with Streamlit.

Key Features ✨
Multi-Disease Classification: Identifies several common citrus diseases including Canker, Greening, and Black Spot, and distinguishes them from healthy leaves.

Model Bake-Off: A comparative study between MobileNetV2 and InceptionV3 to evaluate the trade-offs between model size, speed, and accuracy.

Interactive Web Application: A simple and intuitive UI built with Streamlit that allows users to upload a leaf image and receive an instant diagnosis.

In-depth Performance Analysis: Includes detailed evaluation metrics, a confusion matrix, and an analysis of misclassified images to understand the model's limitations.
