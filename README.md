# PlantDiseaseDetection

## Overview

A real-time plant disease detection and multi-object tracking system built with YOLOv8. The system processes video streams, detects diseased plant regions, maintains persistent tracking across frames, and provides explainable AI visualizations for agricultural diagnostics.

## Features

- Real-time disease detection using YOLOv8 trained on a custom dataset
- Multi-object tracking with persistent track IDs and confidence scores across video frames
- End-to-end video processing pipeline built in Google Colab with OpenCV
- Annotated MP4 output generation optimized for production deployment
- Explainable AI integration using Grad-CAM and LIME for model decision visualization
- Interpretable agricultural diagnostics for precision farming applications

## Tech Stack

- YOLOv8 for object detection
- OpenCV for video processing
- Google Colab for pipeline execution
- Grad-CAM and LIME for explainable AI
- Python

## Pipeline Workflow

1. Input video is loaded into Google Colab environment
2. YOLOv8 model processes each frame for disease detection
3. Multi-object tracking assigns persistent IDs to detected regions
4. Confidence scores are calculated and assigned to each track
5. Grad-CAM and LIME generate heatmaps for model interpretability
6. Annotated video with bounding boxes, track IDs, and confidence scores is exported as MP4

## Output

The system generates an MP4 video file with the following annotations:
- Bounding boxes around detected diseased plant regions
- Unique track IDs for each detected region across frames
- Confidence scores for each detection
- Optional Grad-CAM/LIME overlay for explainability

## Use Cases

- Precision farming and crop monitoring
- Early disease detection in agricultural fields
- Research and development in plant pathology
- Automated greenhouse surveillance systems

## Acknowledgments

This project demonstrates the application of computer vision and explainable AI techniques for agricultural technology.
