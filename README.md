# Multimodal Post Stroke Recovery Prediction using Audio Visual Deep Learning

This project presents a multimodal deep learning framework for post-stroke recovery prediction using synchronized audio-visual biomarkers extracted from clinical examination recordings. The system integrates facial landmark dynamics, speech-based acoustic features, and metadata representations to enable automated neurological impairment assessment.

---

## Overview

Post-stroke neurological disorders often manifest through subtle facial asymmetry, speech impairment, and motor function irregularities. This project leverages a multimodal learning approach combining:

- Video-based facial landmark feature extraction  
- Audio signal representation learning  
- Clinical metadata encoding  
- Deep multimodal fusion architecture  

to improve predictive performance over traditional unimodal screening approaches.

---

## Dataset Used

This project utilizes the **Toronto NeuroFace Dataset**, a clinically annotated multimodal dataset designed for the analysis of neurological disorders such as stroke and ALS.

The dataset contains:

- Facial expression videos of patients with neurological impairment  
- Corresponding synchronized speech recordings  
- Clinical severity scores assigned by trained clinicians  
- Manually annotated facial landmarks on representative frames  

It includes over **261 clinical video recordings and 3300+ annotated facial landmark frames** collected from individuals with post-stroke neurological conditions and age-matched healthy controls. :contentReference[oaicite:0]{index=0}

These recordings are captured during standardized orofacial assessment tasks commonly used in neurological screening, enabling automated analysis of facial motion patterns associated with post-stroke impairment. :contentReference[oaicite:1]{index=1}

---

## System Architecture

The proposed pipeline consists of:

- Video-only feature extraction pipeline  
- Audio feature encoder  
- Metadata encoder  
- Multimodal fusion model  
- Audio-visual joint inference system  

Feature representations from multiple modalities are fused using deep neural architectures to capture cross-modality correlations for improved stroke prediction.

---

## Repository Structure