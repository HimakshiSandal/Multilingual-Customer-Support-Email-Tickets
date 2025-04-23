# 📬 Multilingual Customer Support Email Ticket Classification

This data science project focuses on building a machine learning model to automatically classify customer support emails written in multiple languages. The model helps determine the **priority** (e.g., high or low) and the appropriate **queue category** (e.g., technical, billing, etc.) for each ticket, enabling faster and more efficient support operations.

## 🧾 Project Objective

- **Goal**: Automate the classification of incoming support tickets based on their content.
- **Tasks**:
  - Identify ticket **priority** (High/Low)
  - Assign tickets to appropriate **queues**
- **Result**:
  - **Priority classification accuracy**: **88.75%**
  - **Queue classification accuracy**: **53.13%**

## 📂 Key Features of the Project

- Worked with multilingual email data to build a robust classification pipeline.
- Applied **text preprocessing techniques** including:
  - **Tokenization** – Split text into individual words/tokens
  - **Stopwords Removal** – Removed commonly used words that don’t carry meaningful info (e.g., “the”, “is”)
  - **Stemming & Lemmatization** – Reduced words to their root/base form
  - **TF-IDF Vectorization** – Converted text into numerical features
- Used **Random Forest Classifier** for both classification tasks.
- Visualized model predictions using **scatter plots** to analyze results.

## 🧠 Machine Learning Models

- Model used: **Random Forest Classifier**
- Evaluation metrics: **Accuracy**, **Classification Report**, **Confusion Matrix**
- Trained two models:
  - Priority Classifier → 88.75% accuracy
  - Queue Classifier → 53.13% accuracy

## 🧰 Tools & Technologies

- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn  
- **Environment**: Jupyter Notebook / VS Code  
- **Version Control**: Git, GitHub
