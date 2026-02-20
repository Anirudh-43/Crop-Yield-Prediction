# 🌾 **Crop Yield Prediction**

## 📌 **Overview**
This project simulates agricultural data and builds a **deep learning regression model** using **TensorFlow** to predict crop yield (**tons/hectare**).  

It demonstrates how **machine learning** can support **agricultural decision-making** and **precision farming**.

---

## 🎯 **Features**
- ✅ **Simulated agricultural dataset**  
- ✅ **Neural network regression model**  
- ✅ **Model evaluation using MAE**  
- ✅ **Visualization of predicted vs actual yield**

---

## 📊 **Input Features**
- **Soil Quality**  
- **Rainfall**  
- **Temperature**  
- **Fertilizer Use**  
- **Pesticide Use**  

**Target Variable:** **Crop Yield (tons/hectare)**

---

## 🧠 **Model Architecture**
- **Dense Layer:** 64 units, ReLU activation  
- **Dense Layer:** 32 units, ReLU activation  
- **Output Layer:** 1 unit  

**Loss Function:** MSE  
**Evaluation Metric:** MAE  
**Optimizer:** Adam  

---

## 🛠️ **Technologies**
- **Python**  
- **TensorFlow (Keras)**  
- **NumPy**  
- **Scikit-learn**  
- **Matplotlib**

---

## 🚀 **How to Run**

```bash
git clone https://github.com/yourusername/crop-yield-prediction.git
cd crop-yield-prediction
pip install -r requirements.txt
python crop_yield_model.py
