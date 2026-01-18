AI-Powered Fashion Search Engine: Evolution of Semantic Discovery

This repository contains a three-stage evolution of a high-precision Fashion Retrieval System. Using the Fashionpedia dataset, this project progresses from a basic multi-vector search to a state-of-the-art dual-VLM (Vision-Language Model) ensemble capable of understanding both technical attributes and narrative human intent.
🚀 Repository Structure

The project is divided into three standalone notebooks, each representing a major architectural milestone:

    Version_1_Decomposed_Baseline.ipynb: Multi-vector indexing and basic reranking.

    Version_2_Vision_First_Hybrid.ipynb: Visual color correction and search-by-image.

    Version_3_Semantic_Ensemble.ipynb: Dual-captioning with Florence-2 + BLIP and consensus reasoning.

Version 1: The Decomposed Semantic Baseline

# The foundational approach treats images as a collection of five distinct semantic paths (Global, Clothing, Color, Scene, and Style). It uses a lightweight L-6 Cross-Encoder to verify results.

Architecture Diagram of Version-1
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/208dbf9b-36eb-4936-9cb2-20ea85ea6006" />


Version 2: The Vision-First Hybrid Engine

# Introduces a Visual Oracle logic. It doesn't just trust metadata; it uses CLIP to visually verify colors and introduces Search by Image functionality.

Architecture Diagram of Version-2
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/364379d9-9dd3-49d5-b4d4-b2ecb7d4810f" />


Version 3: The Dual-VLM Semantic Ensemble

# The final version achieves Semantic Completeness by ensembling Florence-2 (technical details) and Salesforce BLIP (natural language). It uses a 7-dimensional vector index.

Architecture Diagram of Version-3
<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/45fb297a-ad3d-47a6-bd84-35bda1312d21" />

