# Deception Detection System with Joint Cross-Attention

**Authors:** Peili Jiang, Yunfan Wang, Jiajun Li, Ziyang Wang
**Affiliations:** New York University, The University of New South Wales, University of California-San Diego, Carnegie Mellon University

## Abstract

This research focuses on deception detection, combining facial landmarks, action units (AUs), and audio emotion units (EUs) to analyze facial expressions and emotional changes for deception detection. The proposed method uses a Joint Cross-Attention model and SVM for classification. The study is based on the Real-Life Trial Data and MSP-YTD datasets, demonstrating promising results for deception detection.

## Introduction

Deception detection is crucial in various fields, such as law enforcement and psychology. Traditional methods like polygraphs face reliability issues, and this research introduces a non-contact approach using computer vision and audio analysis to detect deception through facial indicators.

## Related Work

The study explores both verbal and non-verbal deception detection methods, integrating linguistic and non-verbal cues. The research aims to combine these elements for improved accuracy in deception detection.

## Datasets

The study uses two datasets: Real-Life Trial Data and MSP-YTD, both containing videos with deceptive and truthful content for experimentation.

## Methods

The proposed method involves facial landmark detection, extraction of Action Units (AUs) and Emotion Units (EUs), and the use of a Joint Cross-Attention model for audio-visual fusion. Support Vector Machines (SVM) are used for deception classification.

## Experiments

The research employs 3-fold cross-validation on the datasets. The accuracy of deception detection is evaluated based on the extracted features and SVM classification. The results demonstrate the effectiveness of the proposed method.

## Conclusion

The study's approach, combining AUs, EUs, and Joint Cross-Attention, shows promise in deception detection. Future work may focus on improving feature robustness and considering speech analysis.

