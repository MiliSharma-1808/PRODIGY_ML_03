# PRODIGY_ML_03 - Cats vs Dogs Classification with Support Vector Machine (SVM)

This project is part of the **Machine Learning Internship** offered by **Prodigy InfoTech**.

---

## 📊 Task Objective

Implement a **Support Vector Machine (SVM)** classifier to distinguish between images of **cats** and **dogs** using the [Kaggle Dogs vs Cats dataset](https://www.kaggle.com/c/dogs-vs-cats/data).

---

## 📌 Dataset Source
**Kaggle:** [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data)

---

## 🔧 Tools & Libraries Used

- Python 🐍
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Kaggle API

---

## 📈 Approach

- Downloaded and extracted the dataset from Kaggle  
- Loaded images and resized them to a smaller fixed size for efficient SVM training  
- Converted images to **color format** and normalized pixel values  
- Flattened image arrays for SVM input  
- Split dataset into training and testing sets  
- Trained a **Support Vector Classifier (SVC)** model  
- Evaluated performance using **accuracy score**  
- Visualized predictions on random test images

---

## 📝 Notes on Dataset Usage

For this project, I used a **subset** of the original Kaggle dataset rather than all 25,000 images.  
- **Reason:** Training an SVM on the full dataset is computationally intensive and time-consuming.  
- Using a smaller subset speeds up preprocessing and model training while keeping the dataset **balanced** between cats and dogs.  
- This approach allowed for faster experimentation and easier tuning of the SVM model.  

---

## 🐾 Single Image Prediction

In addition to testing on the dataset, the model can predict the class of a **single uploaded image**.  

**How it works:**  
1. Load the image with OpenCV.  
2. Resize it to `64x64` pixels (same as training images).  
3. Flatten the image to a 1D array for SVM input.  
4. Use the trained model to predict the class.  
5. Output `"Cat"` or `"Dog"`.  


---

## ✅ Results

- Achieved classification accuracy of **0.67** on test data  
- Successfully predicted labels for unseen images  



---

## 📁 Files

- `PRODIGY_ML_03.ipynb` → Full implementation notebook  
- `README.md` → Project overview  
- `sample_predictions.png` → Output visualization  

---

## 🔗 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MiliSharma-1808/PRODIGY_ML_03/blob/main/PRODIGY_ML_03.ipynb)

---

## 🚀 Output Preview

![Sample Predictions](sample_predictions.png)

---

## 📚 Learning Outcomes

- Learned how to apply **SVM** to an image classification problem  
- Understood preprocessing techniques for image-based ML models  
- Improved skills in **dataset handling** and **model evaluation**  

---

## 📝 Note

✅ This repository is maintained as part of the **Prodigy InfoTech Machine Learning Internship**.


