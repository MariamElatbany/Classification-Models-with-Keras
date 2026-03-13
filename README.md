# 🖥️ Classification Models with Keras ✨

This repository demonstrates **classification models** using **Keras** on the **MNIST dataset** of handwritten digits.  

---

## 🌟 Features
- **🧹 Data Preprocessing & Normalization:** Flatten images, normalize pixel values to scale inputs.  
- **🖼️ Feature Extraction:** Prepare inputs for neural networks.  
- **🧠 Neural Network Models:** Build dense networks for classification.  
- **📊 Training & Evaluation:** Fit models, track accuracy, and compute error rates.  
- **💾 Saving & Loading Models:** Save trained models and reload for predictions.  

---

## 🚀 Usage
1. **Load Dataset:** `mnist.load_data()` from Keras.  
2. **Preprocess:** Flatten images and normalize values (0-1).  
3. **Transform Labels:** Use `to_categorical()` for one-hot encoding.  
4. **Build Model:** Use `Sequential()` API and `Dense` layers with `relu` and `softmax`.  
5. **Train Model:** Fit model using `fit()` with training and validation sets.  
6. **Evaluate Model:** Use `evaluate()` to check accuracy and error rate.  
7. **Save & Load Model:** `model.save()` & `keras.saving.load_model()`.  

