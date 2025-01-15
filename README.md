# Chest X-ray Medical Image Retrieval System

=> I made a Chest X-ray Medical Image Retrieval System using Vision Transformers (ViT) and Contrastive Learning.

=> The system achieves state-of-the-art performance with a Mean Average Precision (mAP) of 99.8%, demonstrating 
its capability for highly accurate medical image retrieval.

=> The system is designed to retrieve the most relevant chest X-ray images from a database, aiding in
diagnostic and comparative analysis.

# Features
1. Retrieval of similar chest X-ray images based on query input from test data.
2. Use of Vision Transformer (ViT) for feature extraction.
3. Contrastive learning for effective embedding space representation with modified contrastive loss function and differential regularization.
4. Performance evaluation using metrics such as Mean Average Precision (mAP), Precision@K, and Recall@K.

# Novel Contributions

=> Modified Contrastive Loss Function: Enhanced the loss function to better separate embedding vectors of
similar and dissimilar images, resulting in a more robust embedding space.

=> Improved Differential Regularization: Introduced modifications to the regularization mechanism to reduce overfitting and improve
generalization, leading to a significant boost in mAP from 96.9% to 99.8%.

=> Optimized the feature extraction pipeline for high-dimensional medical images, ensuring scalability and retrieval efficiency.


# Acknowledgements
This work was conducted as an independent research project and I extend my
gratitude to the open-source community for providing tools and resources for implementation.

## References

This project builds upon the methodologies presented in the following paper:

- Arvapalli Sai Susmitha and Vinay P. Namboodiri, "Analysis of Transformers for Medical Image Retrieval," *Proceedings of Machine Learning Research*, vol. 211, pp. 1–16, 2024. [Available online](https://openreview.net/forum?id=7w5IHAybj3).

### Dataset

This project uses the COVID-19 posterior-anterior chest radiography images (X-rays) dataset:

- **Unais Sait, KG Lal, S Prajapati, Rahul Bhaumik, Tarun Kumar, S Sanjana, and Kriti Bhalla**,  
  "Curated dataset for COVID-19 posterior-anterior chest radiography images (X-rays),"  
  _Mendeley Data_, 1, 2020.  
  [Available online](https://data.mendeley.com/datasets/whateverlink).


