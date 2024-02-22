# SOEN-471 Project
Overview
Plant Disease Diagnosis using Neural Expert System is an Artificial Neural Network (ANN) processing paradigm that is inspired by the way biological nervous systems, such as the brain, process information. This project focuses on developing a Neural Expert System for the diagnosis of plant diseases. The aim is to leverage machine learning techniques to create an accurate and efficient system that can identify diseases in plants based on visual symptoms. The system employs neural network models to analyze images of plants and make predictions about the presence of diseases.

Dataset
The dataset used for training and evaluation consists of a diverse collection of plant images, each labeled with the corresponding disease category. The dataset comprises images of various plant species, and each image is associated with metadata such as plant type, environmental conditions, and disease status. It includes 54,305 images of leaves. 
https://www.kaggle.com/datasets/saroz014/plant-disease/code


Dataset Characteristics:
•	Number of Images: 54305 

Research Questions
1.	Accuracy of Diagnosis: How accurately can the neural expert system identify plant diseases based on visual symptoms in the given dataset?
2.	Generalization: How well does the model generalize to different plant species and environmental conditions?
3.	Diversification: How does the size and diversity of the training dataset impact the performance and generalization ability of the neural expert system for plant disease diagnosis?

Model Design
Our system utilizes deep Convolutional Neural Networks (CNNs) for effective plant disease detection. The CNN analyzes plant images to identify visual symptoms associated with diseases. A Neural Knowledge Base collaborates with a Fact Database, leveraging neural networks to understand disease relationships. The Fact Database contains domain-specific information about symptoms and recommended treatments. The integrated system provides insightful suggestions for disease management, such as pesticides or fungicides. User-friendly and interactive, the model aims to contribute to efficient and informed decision-making in agriculture.

Algorithms
The proposed system employs two key algorithms, each serving a distinct purpose:
1.	CNN-based Disease Identification Algorithm:
•	Objective: Utilizes deep Convolutional Neural Networks (CNNs) to analyze visual symptoms in plant images.
•	Operation: Processes images through convolutional layers, capturing hierarchical features for disease detection.
•	Outcome: Provides accurate identification of diseases based on visual cues extracted from images.
2.	Neural Knowledge Base and Fact Database Integration Algorithm:
•	Objective: Integrates the Neural Knowledge Base with the Fact Database for informed decision-making.
•	Operation: Leverages neural networks to correlate visual symptoms identified by the CNN with domain-specific facts.
•	Outcome: Generates context-aware suggestions for disease management, aligning recognized symptoms with established knowledge.


References
•	Plant Disease Detection. https://arxiv.org/pdf/1604.03169.pdf 
![image](https://github.com/Priyanshu2726/SOEN-471-Project/assets/106572510/09ce87fa-d976-400a-87bb-35f57d8f6933)
