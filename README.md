# Detect-Assignment
# Edge AI Smart Factory Vision System

This repository contains the system design and architecture for a real-time
multi-camera intelligent vision system targeting smart factory environments.

## Overview
The system is designed for deployment on NVIDIA Jetson edge devices and uses
NVIDIA DeepStream, TensorRT, and Transfer Learning Toolkit (TLT) to perform
real-time object detection, semantic segmentation, video analytics, and
anomaly detection under strict latency and power constraints.

## Repository Contents
- Smart_Factory_Edge_AI_Vision.pdf – Main submission document
- Appendix_A_System_Details.pdf – Optional technical appendix
- architecture_diagram.png – System architecture diagram

## Notes
- The design is validated using NVIDIA DeepStream reference pipelines and
  published Jetson benchmarks.
- Jetson hardware access was not available during development.
- All real-time inference is designed to run fully on the edge.

## Technologies
- NVIDIA DeepStream
- TensorRT
- Transfer Learning Toolkit (TLT)
- NVIDIA Jetson
