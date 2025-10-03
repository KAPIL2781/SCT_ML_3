# SCT_ML_3
Machine Learning Task 3 – Cat vs Dog Image Classification

# 🐾 Cat vs Dog Classification Using SVM

## 📌 Problem Statement  
Implement a **Support Vector Machine (SVM)** to classify images of cats and dogs from the Kaggle Cats vs Dogs dataset.  

The goal is to accurately distinguish between cat and dog images and visualize model performance for better understanding.

## 📊 Dataset  
We used the **Cats vs Dogs dataset**:  
👉 [Dataset Link](https://www.kaggle.com/c/dogs-vs-cats/data)  

Selected features for classification:  
- **RGB pixel values** from resized images (64x64).  

A subset of 1000 images per class was used for faster processing. Images were resized and flattened for SVM input.

## ⚙️ Steps Followed  

1. **Data Loading & Exploration**  
   - Unzipped the dataset in Google Colab.  
   - Selected 1000 cat and 1000 dog images.  

2. **Data Preprocessing**  
   - Loaded RGB images using **PIL**.  
   - Resized images to 64x64 and flattened to vectors.  

3. **Data Splitting**  
   - Split data into 80% training and 20% testing sets.  

4. **SVM Classification**  
   - Trained an SVM with **RBF kernel** and probability estimates.  

5. **Visualization**  
   - Plotted **confusion matrix**, **precision-recall curve**, and **ROC curve**.  
   - Created a **2x3 image grid** of colored predictions using **Matplotlib**.  

6. **Model Evaluation**  
   - Calculated accuracy and classification metrics for cat and dog classes.  

## ▶️ How to Run the Code  

1. Open a new notebook in **Google Colab**.  
2. Upload `train.zip` into Colab’s Files section.  
3. Run all cells sequentially to preprocess data, train SVM, and generate visualizations.  

## 📈 Results  

- **Accuracy**: Achieved a test accuracy of approximately XX% (run code to get exact value).  
- **Confusion Matrix**: Shows true vs. predicted labels.  
- **Precision-Recall & ROC Curves**: Visualize model performance.  
- **Image Grid**: Displays 6 colored test images with true and predicted labels.  


## 📦 Tech Stack  
- Python  
- NumPy  
- Scikit-learn (SVC, metrics)  
- PIL (Pillow)  
- Matplotlib, Seaborn  
- TQDM  
- Google Colab  

## ✨ Author  
**Kapil**  
📍 [CSE (AI - ML), Chitkara University]  
