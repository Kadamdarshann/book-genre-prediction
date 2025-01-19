# Book Genre Classification Project 📚✨

This project focuses on **Book Genre Classification**, where a machine learning model predicts the genre of a book based on its summary. Genres include thriller, science fiction, fiction, history, and more. This natural language processing (NLP) task follows a structured workflow from data preprocessing to model deployment.

---

## 🚀 Workflow Overview

### 1. **Data Loading**
- The dataset is loaded into a dataframe for analysis and processing.
- A link to download the dataset will be provided.

### 2. **Data Preprocessing**
- Preprocessing involves cleaning and preparing text for NLP tasks.
- Techniques include:
  - Tokenization
  - Stemming
  - Lemmatization
  - Removal of stopwords, punctuations, and other noise

### 3. **Exploratory Data Analysis (EDA)**
- Perform EDA to analyze the stemmed words and text patterns.
- Visualizations are created to understand the dataset better.

### 4. **Model Selection**
- Evaluate and select the best machine learning algorithm for the task.
- Train the model using the processed data.
- Save the model weights for future use.

### 5. **Integration with Web Service**
- The trained model is integrated into a web application using a web framework like Flask or Django.

### 6. **Deployment**
- Deploy the web application to AWS EC2 for real-time predictions.

---

## 🖥️ Demo

### Workflow of the Application:
1. Input a book summary into the application.
2. Hit the **Predict** button.
3. The application processes the input and classifies it into a genre.
4. Predictions may take some time due to heavy backend processing.

#### Example:
- Input: A summary describing a chemical spill and survival story.
- Predicted Genre: Thriller
- **Explanation:** The model identifies key elements (e.g., struggle, survival, and high stakes) to classify it as a thriller.

---

## 📂 Dataset Information
- The dataset used for this project is publicly available.  
- BooksDataSet.csv 

---

## 📜 How to Run the Project Locally
### Prerequisites:
- Python 3.x
- Required Python libraries (listed in `requirements.txt`)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Kadamdarshann/book-genre-prediction.git
   cd book-genre-prediction
