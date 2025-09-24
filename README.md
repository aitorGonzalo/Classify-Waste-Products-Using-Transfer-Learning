# Classify Waste Products Using Transfer Learning

---

## 📝 Introduction
This project is part of the **IBM AI Engineer Specialization** on deep learning (CNN and Transfer Learning).  

EcoClean currently lacks an efficient and scalable method to automate the waste sorting process. Manual sorting is labor-intensive and prone to errors, which can lead to contamination of recyclable materials.  

This project leverages **deep learning and computer vision** to automate waste classification, improving efficiency and reducing contamination rates.  

The system uses **transfer learning** with a pre-trained **VGG16 model** to classify images into **recyclable** and **organic waste** categories. By reusing knowledge from ImageNet, high accuracy is achievable even with a limited dataset.

---

## 🎯 Aim of the Project
The aim is to develop an automated waste classification model that differentiates between recyclable and organic waste based on images.  

**Final Output:** A trained and evaluated model capable of classifying waste images into recyclable and organic categories for real-world integration.

---

## 🛠 Objectives
- Train a transfer learning model using a pre-trained **VGG16 convolutional base**  
- Build a classifier on top of the convolutional features to distinguish between recyclable and organic waste  
- Fine-tune the model by unfreezing deeper layers to improve dataset-specific accuracy  
- Visualize model performance through **accuracy and loss curves** for both training and validation  
- Test the model on new images and visualize predictions  

---

## 🔄 Project Workflow
1. **Data Preparation:** Load and preprocess images of recyclable and organic waste  
2. **Feature Extraction:** Use VGG16 convolutional base to extract high-level image features  
3. **Classifier Training:** Train a dense classifier on top of extracted features  
4. **Fine-Tuning:** Unfreeze the deepest layers of VGG16 for improved performance  
5. **Evaluation:** Assess both the feature-extraction model and fine-tuned model on test data  
6. **Visualization:** Plot test images with actual and predicted labels to visually assess predictions  

---

## 📈 Results
- **Feature Extraction Model:** Achieves reasonable accuracy by training only the classifier  
- **Fine-Tuned Model:** Improves performance by adapting selected VGG16 layers to the dataset  
- Visualizations demonstrate correct predictions and highlight potential misclassifications  

---

## ✅ Conclusion
This project demonstrates the power of **transfer learning** for image classification tasks with limited datasets.  
By combining pre-trained convolutional features with a custom classifier and selective fine-tuning, it is possible to create a robust model for waste sorting.  

The methodology is **generalizable** to other image classification problems requiring high accuracy without extensive datasets.
