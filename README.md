# Posture Extraction and Deduplication in Jathiswaram Dances via Similarity Filtering

This repository will contain the official implementation of the paper: _Posture Extraction and Deduplication in Jathiswaram Dances via Similarity Filtering_.

**Status**: Under Review in the _4th International Conference on Machine Learning and Data Engineering (ICMLDE 2025), Elsevier_. [[Link]](https://www.icmlde.org/)

## Overview
Classical Indian dance forms like **Bharatanatyam** present rich, codified movement vocabularies that are challenging to analyze computationally due to rhythmic complexity and semantic depth.  
In this work, we propose the **first systematic framework** for posture-level deduplication in **Jathiswaram**, a core non-narrative (nritta) limbic item of Bharatanatyam.

<img width="1180" height="576" alt="image" src="https://github.com/user-attachments/assets/fc865a19-cf03-4784-819d-a63fc8c31790" />

## Key Highlights
- **Annotated Dataset**: 400 manually annotated postures from five Jathiswaram performances across different Ragas.  
- **Novel Framework**: Lightweight, interpretable, and tailored for small datasets.  
- **Applications**: Choreographic analysis, cultural archiving, intelligent tutoring systems, and generative dance modeling.

Our pipeline integrates:  
- **MediaPipe Pose** for 33-keypoint skeletal landmark detection  
- **Normalization techniques** for translation and scale invariance    
- **Greedy deduplication algorithm** with F1-based threshold optimization  

Among all metrics, **Angular Distance** achieved the best performance, yielding **84.01% accuracy** and a **76.19% F1-score** on unseen sequences.

## ⏳ Code Release
The source code, dataset preprocessing scripts, and evaluation pipeline will be released **after the review process is complete** and the decision of ICMLDE 2025 is announced.  

### Acknowledgements
I thank Dr. S. Karthika, and Dr.R. Srinivasan_ for the opportunity to collaborate and advising me on this work.
