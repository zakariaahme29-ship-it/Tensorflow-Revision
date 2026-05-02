# Level 2: Computer Vision & Convolutional Neural Networks (CNNs)

Welcome to the second phase of the TensorFlow Revision repository. This level focuses on teaching machines how to "see" and interpret visual data using advanced Neural Network architectures.

## 🔗 Contents of this Level:

*   **Acute_Lymphoblastic_Leukemia_(ALL)_Classification.ipynb**: A comprehensive project demonstrating how to build a Convolutional Neural Network (CNN) from scratch using TensorFlow and Keras. This notebook covers the end-to-end pipeline of classifying Acute Lymphoblastic Leukemia (ALL) from microscopic blood smear images.
    *   **Architecture Upgrade**: Unlike Level 1 where we manually mapped and normalized the data in the pipeline, this model integrates a `tf.keras.layers.Rescaling` layer *directly* into the sequential model. This ensures normalization is baked into the architecture itself!
    *   **Techniques Covered**: Data preprocessing, building `Conv2D` and `MaxPooling2D` layers, pipeline optimization (Caching & Prefetching), and performance visualization.

*More advanced computer vision projects and object detection architectures will be added to this section soon.*
