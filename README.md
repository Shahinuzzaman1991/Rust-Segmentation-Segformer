Real-Time Rust Segmentation on Steel Surface Using a Lightweight Transformer Deep Learning Model
Introduction: This repository contains the implementation of Real-Time Rust Segmentation on Steel Surfaces, leveraging the power of the lightweight SegFormer model. Designed for efficiency and accuracy, this project utilizes a transformer-based deep learning architecture to segment rust areas on steel surfaces in real time. Built with Lightning PyTorch, the framework ensures scalability, modularity, and seamless training and inference pipelines. The project aims to provide a robust solution for rust identification in industrial applications, helping to enhance maintenance processes and improve structural safety. Explore the code and models to see how state-of-the-art transformer technology meets real-world challenges.

Methodology: We collected our dataset from various sources to enhance accessibility and ensure diversity in the image sets. Next, we utilized annotation tools to create mask images. Subsequently, we employed three deep learning models—SegFormer, DeepLabV3+, and U-Net—to segment objects from the images. Finally, we evaluated our models using TensorBoard for performance analysis.

Result: A confusion matrix was utilized to evaluate the performance of deep learning models on a rust image dataset, with metrics including precision, accuracy, recall, the Dice coefficient (F1 Score), and intersection over union (IoU). The dataset comprised 203 rust images, including augmented samples, which were used to train the SegFormer deep learning model. The dataset was split into three subsets: 80% for training, 20% for validation, and 10% for testing.

Read me.pdf

 

