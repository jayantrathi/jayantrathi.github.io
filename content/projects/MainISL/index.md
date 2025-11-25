---
title: Sound Based Danger Detection AI
date: 2023-10-26
links:

tags:
  - Intelligent Systems Lab 
  - HugoBlox
  - Markdown
---

Technologies: Python, YAMNet embeddings, SVM classifier, TensorFlow Lite, CCTV audio extraction, ESP32 microphones, Firebase

This was my main project during the time I was a part of both the ISL and Baksters Limited.

This project is an audio based safety system designed to detect dangerous or urgent events in real time using machine-learning.

• Built an end-to-end pipeline that extracts audio from ESP32 microphones and converts raw sound into machine learnable embeddings using YAMNet.

• After having trouble trying to create a ground up model with Keras, my team choose to train SVM classifiers to recognize high risk audio patterns such as glass breaking, screaming, falls, and baby crying by feeding them structured embedding vectors instead of raw waveforms.

• Developed a labeled dataset of diverse "danger" sounds with balanced examples of background noise to ensure proper model generalization.

• Achieved strong performance improvements for specific danger classes (glass break and baby cry), demonstrating the advantage of embedding based classification over pure CNN audio models.

• Integrated real-time alerting through Firebase and LINE notifications to immediately warn users when a dangerous sound is detected with the location of the sound too.

• Positioned the system as a lightweight, camera-free safety layer that operates regardless of lighting, visibility, or field-of-view constraints allowing users to maintain their privacy but be able to look after their home and their loved ones from anywhere.
