
# Image Collection Summarization Using Scene Graph Generation
This project focuses on summarizing image collections by generating scene graphs that capture spatial and semantic relationships. The approach integrates object detection, contextual embeddings, and external knowledge to create enriched representations of image datasets.

# Table of Contents
Overview

Features

Dataset

Installation

Results

Future Work

Contributors

# Overview
With the rapid growth of digital image collections, understanding relationships within these datasets is essential. This project leverages scene graph generation to create meaningful summaries of image collections, enabling advanced analysis across domains like media organization, visual search, and digital archiving.

# Key Components:
Object Detection: RetinaNet with ResNet-50 backbone for detecting objects in images.
Feature Extraction: VGG16 to extract feature vectors for detected objects.
Contextual Embeddings: BiLSTM for capturing object relationships.
External Knowledge Integration: ConceptNet to enhance semantic context using graph convolutions.
Scene Graph Generation: IoU-based spatial relationship modeling and semantic merging.

# Features
Detailed Scene Graphs: Captures spatial, semantic, and external knowledge-based relationships.
Flexible Integration: Supports knowledge graph enrichment for enhanced insights.
Scalable Processing: Handles large image collections effectively.
Dataset
The project uses the MS COCO Dataset https://cocodataset.org/#download .

# Download Instructions:
Go to the COCO website and download the 2017 training, validation images, and annotations.
Place the data in a data/COCO directory within the project.
Installation
Prerequisites
Python 3.7+
GPU-enabled environment for faster processing (optional)

# Results
Graph Representations: Generated scene graphs incorporate spatial and semantic relationships, with enhanced insights through external knowledge integration.
Performance Metrics: Improved object detection accuracy and relational modeling compared to baseline methods.
Example outputs can be found in the outputs/visualizations folder.

# Future Work
Advanced Knowledge Integration: Explore additional knowledge graphs for richer semantic context.
Real-Time Processing: Optimize for real-time applications in robotics and AR/VR.
Cross-Modal Analysis: Extend to incorporate textual and audio data for multimodal summarization.

# Contributors
Khushi Suresh Muddi

Shreya Suresh Jindrali

Shikha Reji
