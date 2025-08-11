---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. candidate in Cyberspace Security, Beijing University of Posts and Telecommunications, 2026 (expected)
* B.S. in Network Engineering, Beijing University of Posts and Telecommunications, 2020

Work Experience
======
* July 2025 - Present: Intern
  * ByteDance, Jindouyun Talent Plan
  * Duties included: Leading the technical design of a multimodal medical large language model for video consultations. My role involves developing a dual-track "synthetic + real" data strategy and building a clinically-oriented evaluation set to extract "digital biomarkers."
 
Research Experience
======
*All projects are first-author or student first-author works.*
* Feb 2025 - Present: Steering Generative and Language Models for Early Alzheimer's Diagnosis
  * Project overview: Using a large language model to guide a diffusion model in generating sequential brain images from a single scan, aiming to improve the accuracy of early diagnosis. This work is being prepared for submission to *IEEE Transactions on Knowledge and Data Engineering (TKDE)*.

* Oct 2023 - Feb 2025: Enhancing Foundation Model Fairness through Knowledge Distillation
  * Collaboration: Beihang University
  * Project overview: Developed a method combining hierarchical knowledge distillation with curriculum learning to transfer knowledge from data-rich to data-scarce patient groups. The work, "Curriculum Hierarchical Knowledge Distillation for Bias-Free Survival Prediction," was accepted by IJCAI 2025.

* Dec 2023 - Aug 2024: Correcting Foundation Model Bias with a Hierarchical Diffusion Model
  * Collaboration: Fujian Provincial Cancer Hospital
  * Project overview: Proposed a hierarchical diffusion model to learn the patterns of pathology slides and generate high-quality virtual representations. This approach supplements data for underrepresented patients to correct model bias. The work, "From Representation Space to Prognostic Insights: Whole Slide Image Generation with Hierarchical Diffusion Model for Survival Prediction," was published at AAAI 2025.

* June 2022 - Jan 2024: Building a Robust, Cell-Aware Multimodal Pathology Model
  * Collaboration: Cancer Hospital, Chinese Academy of Medical Sciences
  * Project overview: Constructed a ViT-based model that analyzes both pathology images and cell-graphs and provides an "uncertainty score" to aid physician review. The work, "CTUSurv: A Cell-Aware Transformer-Based Network With Uncertainty for Survival Prediction Using Whole Slide Images," was published in *IEEE Transactions on Medical Imaging (TMI)* in 2025.

* Feb 2022 - Dec 2022: Developing a Trustworthy Pathology Model with Uncertainty and Attribution
  * Collaboration: Microsoft Research Asia
  * Project overview: Proposed the ESAUT framework, which uses a convolution-enhanced ViT and introduces uncertainty into the loss function. The framework also includes a post-hoc explainability method to identify influential image regions and cell features. The work, "Explainable survival analysis with uncertainty using convolution-involved vision transformer," was published in *Computerized Medical Imaging and Graphics (CMIG)* in 2023.

Skills
======
* **Core Research Area**: Multimodal Medical Large Models for complex scenarios
* **Machine Learning Models & Architectures**
  * Large Language Models (LLMs)
  * Generative Models (Diffusion Models)
  * Vision Transformer (ViT) and derivatives
  * Knowledge Distillation
* **AI Concepts & Techniques**
  * Fairness, Bias Correction, and Trustworthy AI
  * Uncertainty Quantification
  * Explainable AI (XAI) / Attribution Analysis
* **Application Domains**
  * Digital Pathology and Oncology
  * Medical Imaging Analysis
  * Alzheimer's Disease Diagnosis

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
