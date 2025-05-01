# Knowledge-Assisted Video Analytics for Suspicious Activity Detection

This project leverages **deep learning** to detect **suspicious activity from surveillance footage** using video analytics. It combines **CNNs** (for feature extraction), **RNNs/LSTM** (for temporal modeling).

## Problem Statement

Surveillance footage is often massive and manually reviewing it is infeasible. This project proposes an intelligent system that:
- Extracts relevant features from video frames
- Classifies actions as *suspicious* or *non-suspicious*

---

## Features
- Frame extraction and preprocessing using OpenCV
- Feature extraction using pretrained CNNs: `VGG16`, `ResNet50`, `InceptionV3`
- Sequence modeling with `LSTM`
- Achieved up to **90% accuracy** with ResNet50 + LSTM

---

## Datasets Used
- [VIRAT Dataset](https://viratdata.org/)
- [CAVIAR Dataset](https://groups.inf.ed.ac.uk/vision/CAVIAR/CAVIARDATA1/)
- [PETS Dataset](http://www.cvg.reading.ac.uk/PETS/)
- [KTH Dataset](https://www.csc.kth.se/cvap/actions/)

---
