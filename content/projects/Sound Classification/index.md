---
title: Sound-Based Human Presence & Door-Event Detection System
date: 2023-03-26
links:

tags:
  - Intelligent Systems Lab
  - HugoBlox
  - Markdown
---
Technologies: Python, TensorFlow/Keras, YAMNet, ESP32 microphones, Firebase, CCTV audio extraction

My first project with the ISL, by the end of which I was introduced into the Baksters organization.

A machine-learning system designed to detect human entrance, exit, and presence events using audio instead of cameras.

• Developed an AI system capable of identifying door events and human-voice signatures by training on real office audio data.

• Collected and curated over 500+ audio clips covering door sounds, human talk, and environmental noise to build a balanced dataset.

• Built a full preprocessing workflow including filtering, normalization to 16 kHz mono, segmentation, and dataset structuring for machine-learning consumption.

• Trained TensorFlow/Keras classification models achieving 90–95% test accuracy across structured training/validation splits.

• Implemented prediction logic on recorded CCTV audio to detect door-open, door-close, and voice events in real time.

• Extended the system using YAMNet embeddings and SVM classifiers to validate alternative sound-classification pipelines.

• Positioned the system as a non-visual human-presence detector, enabling reliable monitoring even in low-visibility or camera-blind scenarios.
