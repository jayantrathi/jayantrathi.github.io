---
title: WiFi-Based Fall Detection System
date: 2023-02-26
links:

tags:
  - Intelligent Systems Lab
  - Project
  - HugoBlox
  - Markdown
---
Technologies: ESP32 (AP/Station), WiFi RSSI sensing, Python, ML classification models, Firebase integration

A non-camera fall-detection system that uses WiFi signal disturbances to recognize when a person has fallen.

• Designed a fall-detection pipeline that interprets fluctuations in WiFi RSSI as indicators of human motion and potential falls.

• Implemented a two-ESP32 setup — one acting as an access point and the other as a station — to collect continuous WiFi packet data for model training.

• Built a large-scale dataset of 8,880 WiFi signal files, containing labeled fall and non-fall events for supervised learning.

• Trained and benchmarked machine-learning models to classify fall events, demonstrating that falls can be detected from RF disturbances even without cameras.

• Identified high false-positive rates in initial models and outlined future improvements including expanded data collection, real-time testing pipelines, and multi-activity WiFi sensing.

• Positioned the system as a privacy-preserving safety layer, enabling fall detection in environments where cameras may not be viable.

⸻

