DATASET LINK: https://www.kaggle.com/datasets/fantacher/neu-metal-surface-defects-data

Overview
This repository contains a detailed Computer Vision Assignment Report focused on detecting metal surface defects using advanced image processing and segmentation techniques. The project leverages traditional and graph-based segmentation models to enhance defect identification and improve industrial quality control.

Dataset
The study is conducted using the NEU Metal Surface Defects Dataset, which consists of labeled images of various defect types such as Inclusion, Scratches, Pitted Surface, and more. The dataset is preprocessed to enhance image quality before segmentation and evaluation.

Key Techniques Implemented
1. Noise Reduction:
Gaussian Blur (Basic Smoothing)
Median Filtering (Effective for Salt-and-Pepper Noise)
Anisotropic Diffusion (Edge-Preserving Noise Reduction)
Adaptive Bilateral Filtering (Best Balance of Smoothing and Detail Preservation)

3. Segmentation Methods:
K-Means Clustering (Clustering-Based Segmentation)
Mean Shift Segmentation (Density-Based Adaptive Clustering)
Graph-Based Segmentation (Enhanced Superpixel-Based RAG Segmentation)
Region Growing (Pixel-Connectivity Based Expansion)
Connected Component Analysis (CCA) (Binary Image Segmentation)

5. Performance Evaluation:
Intersection over Union (IoU)
Dice Coefficient (F1 Score for Segmentation)
Pixel Accuracy

Results & Findings
The report provides a comparative analysis of segmentation methods, where Graph-Based Segmentation proved to be the most effective in terms of accuracy and defect boundary preservation. The Mean Shift Segmentation was also promising but computationally expensive. The Region Growing approach worked well on specific defects but struggled with complex textures.

Conclusion
This project demonstrates the feasibility of automated metal surface defect detection using computer vision. The findings suggest that an optimized combination of Graph-Based Segmentation with Adaptive Bilateral Filtering can serve as a strong foundation for industrial defect detection. Future enhancements may include deep learning-based segmentation methods for improved performance.
