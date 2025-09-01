# 🤖 Income Prediction Chatbot – AI Model with XGBoost

## 📌 Problem  
Predicting a person's income level based on demographic and work-related attributes is important for decision-making in areas such as HR analytics and socio-economic research.  
Traditional models exist, but we wanted to build an **interactive chatbot** that allows predictions directly from free-text input.  

## 🔄 Process  
- Used the **Adult Balanced dataset** as training data  
- Preprocessed data: removed irrelevant features, normalized, encoded categorical variables  
- Trained an **XGBoost Classifier** with 80/20 train-test split  
- Implemented **evaluation metrics**:  
  - Accuracy: 0.85  
  - Precision, Recall, and F1-score all > 0.8  
- Built a **Gradio-based chatbot UI** on Hugging Face  
- Implemented Regex-based NLP to parse user free-text into structured model inputs  

## 🎯 Result  
- An interactive chatbot that predicts whether income is `<=50K` or `>50K`  
- Live deployment on Hugging Face Spaces  
- Achieved strong performance across all metrics (>0.8)  

## 💡 Value  
This project demonstrates my ability to:  
- Combine Machine Learning with product-facing applications  
- Build interactive tools using Hugging Face and Gradio  
- Apply rigorous evaluation (accuracy, precision, recall, F1) to ensure reliability  

---

📷 **Screenshots**  
(Add chatbot UI screenshots here)  
![Chatbot Example](./screenshots/chatbot.png)

🔗 **Live Demo**  
[Hugging Face App]([https://huggingface.co/spaces/top25/income-predictor-bot])  

🛠️ **Tools & Technologies**  
- Python (XGBoost, Pandas, Regex)  
- Google Colab  
- Hugging Face Spaces (Gradio)  
