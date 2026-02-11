# Deep Learning & Computer Vision Portfolio

## 📖 Overview
This repository hosts a collection of deep learning research projects focusing on image classification tasks in agriculture and healthcare. The projects utilize state-of-the-art Convolutional Neural Networks (CNNs) such as **EfficientNet**, **MobileNetV2**, **ResNet50**, and **VGG16** to solve real-world problems.

---

## 🌿 Project 1: Plumbago Zeylanica Classification
**Goal:** Automated identification of the medicinal plant *Plumbago zeylanica* and assessment of its health status.

* **Classes:** The dataset classifies the plant into three categories: **Healthy**, **Unhealthy**, and **Dried**.
* **Models Benchmarked:**
    * EfficientNet-B0
    * MobileNetV2
    * DenseNet201
    * Xception
* **Key Results:** The project analyzes model accuracy and loss to determine the most efficient architecture for identifying this specific medicinal herb.

---

## 🧘‍♂️ Project 2: Pranayama Posture Analysis
**Goal:** A computer vision framework to assist yoga practitioners by classifying breathing exercise postures as correct or incorrect.

* **Dataset:** A custom "Pranayama Dataset" containing approximately **4,000 images**.
* **Classes:**
    * **Correct_way:** Proper posture execution.
    * **Incorrect_way:** Improper form.
* **Models Benchmarked:**
    * EfficientNet-B0
    * MobileNetV2
    * VGG-16
* **Performance:** The models achieved exceptional performance with an **AUC score of ~0.997**, indicating high precision in distinguishing between posture states.

---

## 🍁 Project 3: Thai Cannabis Plant Classification
**Goal:** Classification of specific Thai Cannabis plant varieties to aid in agricultural categorization.

* **Classes:** Includes distinct varieties such as **Foi Thong**, **Hang Kra Rog**, **Hang Suea Sakonnakhon**, **KD KT**, and **Purple Huai Khrai**.
* **Models Benchmarked:**
    * VGG-16
    * ResNet50
    * MobileNetV2
* **Key Results:** Confusion matrices confirm the models' ability to distinguish between visually similar plant strains with high accuracy (e.g., >96% validation accuracy).

---

## 🛠️ Tech Stack
* **Languages:** Python
* **Libraries:** TensorFlow/Keras, OpenCV, NumPy, Matplotlib, Pandas
* **Tools:** Jupyter Notebooks, Google Colab

## 👤 Author
Tanishk Nanadsaheb Shinde
