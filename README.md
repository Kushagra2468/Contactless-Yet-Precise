# Contactless-Yet-Precise

📄 **Research Paper:** [Read the full paper on SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6467392)

## 📌 Overview

Contactless fingerprint recognition has emerged as a hygienic and user-friendly alternative to traditional touch-based systems, especially with the rise of mobile biometrics and post-pandemic public health concerns. However, real-world systems face several challenges such as lighting variations, background noise, inconsistent finger positioning and camera-induced distortions.

This project presents a modern touchless fingerprint authentication framework designed to address these challenges. The system leverages a deep embedding network trained using an advanced triplet learning strategy, featuring:

- Dynamic triplet generation using inverse distance–based probability sampling
- Adaptive margin optimization
- Semi-hard and hard negative mining
- Auxiliary classification supervision for improved inter-class separation
<br>

## 📊 Results

The framework was comprehensively evaluated to test both its specialized accuracy and its ability to generalize across different environments, sensors, and demographics.

### Intra-Dataset Evaluation
*(Evaluated by splitting a single dataset into train, validation, and test subsets)*
- **PolyU Dataset**: Equal Error Rate (EER) of **3.42%**

### Inter-Dataset Evaluation
*(Cross-dataset testing to demonstrate robustness and generalization to unseen data)*
- **Trained on PolyU → Tested on IITB**: Equal Error Rate (EER) of **6.01%**
<br>

## ✅ Conclusion

The results demonstrate strong performance compared to existing state-of-the-art methods, highlighting the robustness and practical viability of touchless fingerprint authentication for real-world and mobile applications.
