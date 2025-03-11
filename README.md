# **Sentiment & Sarcasm Detection Using BERT**  

This project builds a **deep learning model** using **BERT** to classify text into **sentiment categories** (`Negative, Neutral, Positive`) and detect **sarcasm** (`Sarcastic, Not Sarcastic`). The dataset and methodology are based on research available at **[DOI: 10.1016/j.dib.2024.110663](https://doi.org/10.1016/j.dib.2024.110663)**.  

## **🔹 Features**  
✅ **BERT-based NLP model** for sentiment & sarcasm classification.  
✅ **Multi-task learning** for simultaneous classification.  
✅ **Class weight balancing** to handle data imbalance.  
✅ **Optimized for GPU acceleration** (TensorFlow).  

## **🚀 Usage**  
### **1️⃣ Install Dependencies**  
```sh
pip install -r requirements.txt
```
### **2️⃣ Train the Model**  
```sh
python train.py
```
### **3️⃣ Make Predictions**  
```sh
python predict.py --text "Wow, this is the best government ever! (sarcasm)"
```
### **Example Output:**  
```
Predicted Sentiment: Positive  
Predicted Sarcasm: Sarcastic  
```
📌 **For more details, visit [DOI: 10.1016/j.dib.2024.110663](https://doi.org/10.1016/j.dib.2024.110663).** 🚀
