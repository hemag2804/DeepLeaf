
DeepLeaf: A Deep Learning-Based Plant Disease Classification System

DeepLeaf is a deep learning project developed as part of a final-year undergraduate capstone, aimed at addressing the challenges in early detection of plant diseases through image classification. The system is designed to classify diseases in three widely cultivated crops — potato, bell pepper, and apple — using leaf images, thereby contributing to precision agriculture and improved crop management.

Objective

The primary objective of this project is to develop a robust and generalizable plant disease detection model using convolutional neural networks (CNNs). The model is intended to assist farmers and agricultural professionals in diagnosing crop health efficiently through automated image analysis.

Datasets Utilized
->Potato: 2,152 images (Early Blight, Late Blight, Healthy)

->Bell Pepper: 2,475 images (Bacterial Leaf Disease, Healthy)

->Apple: ~300 images (Scab, Rust, Healthy)

All datasets were sourced from publicly available repositories and carefully curated to maintain quality and relevance.

Challenges Addressed
->Class Imbalance: Addressed by assigning class-specific weights during training.

->Limited Dataset Size: Mitigated through extensive data augmentation techniques.

->Generalization Across Crops: Evaluated through cross-validation across different plant species.

Methodology
->Image Preprocessing: Standardized input dimensions, normalization, and augmentation (rotation, zoom, flip, etc.) to increase dataset diversity.

->Transfer Learning: Leveraged pre-trained CNN architectures (e.g., ResNet, MobileNet) to enhance learning efficiency on limited data.

->Class Weighting: Incorporated during training to counteract imbalanced class distributions.

->Cross-Validation: Implemented k-fold validation across crops to assess model robustness and generalizability.

Results
The resulting model demonstrated strong classification performance across all target crop types. It is designed to be lightweight and scalable, making it suitable for deployment in mobile or edge-based applications for real-time field use.

Technologies and Tools
->Programming Language: Python

->Libraries: TensorFlow, Keras, NumPy, Pandas, OpenCV, Matplotlib, Scikit-learn

->Development Environment: Jupyter Notebook

Future Scope
->Deployment on mobile or edge devices for on-field disease detection.

->Integration with IoT sensors or drones for large-scale agricultural monitoring.

->Expansion of the dataset to include additional crops and disease classes for broader applicability.
