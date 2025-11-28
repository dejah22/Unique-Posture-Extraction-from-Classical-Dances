# Posture Extraction, Deduplication and Analysis in Bharatanatyam Dances

This repository will host the official implementation of the article: _Posture Extraction, Deduplication and Analysis in Bharatanatyam Dances_.

**Status**: Under Review in the _Grenze International Journal of Engineering and Technology_. [[Link]](https://thegrenze.com/index.php?display=page&view=journaldetails&id=8)

## Overview
Classical Indian dance forms like **Bharatanatyam** present rich, codified movement and expression vocabularies that are challenging to analyze computationally due to rhythmic complexity and semantic depth.

Moreover, the nuances hidden in each gesture/movement convey rich meanings to the audience based on context, movement combinations and countenance held while performing. This requires precision in motion segmentation, gesture decoding as well as generation, along with large datasets to ensure generalizability.
In this work, we propose the **first systematic framework** for posture-level extraction, deduplication and analysis by taking **Jathiswaram** dances, a core piece in a Bharatanatyam recital.


<img width="1180" height="576" alt="image" src="https://github.com/user-attachments/assets/fc865a19-cf03-4784-819d-a63fc8c31790" />

## Key Highlights
- **Original, Annotated Dataset**: 400+ expert-annotated postures and 3,600+ pose-sequences from Jathiswaram performances across different Ragas.  
- Proposed Framework: A lightweight and interpretable system designed specifically for small, domain-constrained datasets.
The pipeline integrates keyframe sampling with hierarchical heuristics to efficiently extract, filter, and archive posture instances and pose-sequence candidates from continuous video streams.
- Each posture undergoes a structured analysis that evaluates:
         <ol type="i">
          <li> its distinctiveness within the dataset, </li>
          <li> its conformance to codified Bharatanatyam movement grammar (pre-trained on minimal, publicly available datasets on hand mudras, face expressions etc), </li>
          <li> its decomposition into atomic movement components. </li>
- The validated postures are algorithmically recombined into diverse pose-sequence permutations, which serve as inputs for downstream generative modules tasked with synthesizing novel yet grammatically coherent poses.
- **Applications**: Choreographic analysis, cultural archiving, generative motion modeling.

## ⏳ Code Release
The source code, dataset preprocessing scripts, and evaluation pipeline will be released **after the review process concludes** and the editorial decision is communicated.

### Acknowledgements
I thank Dr. S. Karthika, and Dr.R. Srinivasan_ for the opportunity to collaborate and advising me on this work.
