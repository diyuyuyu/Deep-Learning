# 🖼️ Convolutional Neural Networks (CNN) - From Basics to Advanced

This repository is a **step-by-step guide** to understanding and implementing **Convolutional Neural Networks (CNNs)**.  
It covers the **building blocks** like padding, stride, and pooling, and extends into **transfer learning** with pretrained models.

---

## 📂 Topics Covered

### 🔹 1. Image Classification
- **Main Idea**: CNNs classify images into predefined categories.  
- Example: An input image of a 🐶 should be classified as "Dog".  
- CNNs learn features automatically:  
  - Lower layers → edges, colors, textures.  
  - Higher layers → shapes, objects.  

---

### 🔹 2. Padding
- Padding adds extra pixels (usually zeros) around an image before convolution.  
- **Purpose**:  
  - Prevents shrinking of output size.  
  - Preserves important edge information.  
- **Types**:  
  - **Valid Padding** → No padding, output shrinks.  
  - **Same Padding** → Maintains output size = input size.  

---

### 🔹 3. Stride
- Stride defines how many pixels a filter moves across the image.  
- **Examples**:  
  - **Stride = 1** → Moves one pixel at a time → detailed but larger output.  
  - **Stride = 2** → Moves two pixels at a time → smaller output, faster.  
- Larger stride = smaller feature maps.  

---

### 🔹 4. Pooling
- Pooling reduces the spatial size of feature maps while keeping important info.  
- **Types**:  
  - **Max Pooling** → Chooses max value in a patch.  
  - **Average Pooling** → Takes average in a patch.  
- **Benefits**:  
  - Reduces computation.  
  - Prevents overfitting.  
  - Provides translation invariance.  

---

### 🔹 5. Transfer Learning
- **Definition**: Reuse a CNN model trained on a large dataset (like ImageNet) for a new task.  
- **Advantages**:  
  - Faster training.  
  - Works well with small datasets.  
  - Improves accuracy.  
- **Methods**:  
  1. **Feature Extraction** → Freeze pretrained layers, train only new layers.  
  2. **Fine-Tuning** → Unfreeze some deeper layers and retrain.  

---

### 🔹 6. Pretrained Models on ImageNet
- **ImageNet**: Dataset with 14M+ images and 1000 classes.  
- Widely used pretrained CNN models:  
  - **VGG16 / VGG19** – deep and simple.  
  - **ResNet50 / ResNet101** – skip connections to avoid vanishing gradients.  
  - **InceptionV3** – multi-scale filters for efficiency.  
  - **MobileNet** – lightweight for mobile devices.  
  - **EfficientNet** – balances accuracy with efficiency.  

---

## 🚀 Goal of This Repository
By the end of this repository, you will:  
- Understand **classification, padding, stride, and pooling**.  
- Learn how to apply **transfer learning**.  
- Use **pretrained CNN models on ImageNet**.  
- Be able to build CNNs for your own image tasks.  

---

## 🛠️ Requirements
- Python 3.x  
- Jupyter Notebook / Google Colab  
- Libraries:  
  ```bash
  pip install numpy pandas matplotlib scikit-learn tensorflow keras
