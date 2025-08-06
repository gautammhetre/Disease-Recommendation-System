# 🩺 Disease Recommendation System

This is a simple web-based disease recommendation system that suggests possible diseases based on user-input symptoms. It uses **TF-IDF vectorization** and **cosine similarity** to compare the user's symptoms with a predefined dataset of diseases.

## 🔧 Technologies Used

- Python
- Pandas
- Scikit-learn
- Gradio

## 📦 Installation

1. Clone the repository or copy the code.
2. Make sure you have Python installed.
3. Install the required libraries:

```bash
pip install gradio scikit-learn pandas
```
🚀 How to Run
Run the Python script:

```bash
python disease_recommender.py
```
A Gradio interface will launch in your browser.

Enter your symptoms (e.g., fever, cough) and get the top 3 possible disease matches.

📊 How It Works
The system uses TF-IDF to convert disease symptoms into numerical vectors.

When the user enters symptoms, the input is vectorized and compared using cosine similarity.

The top 3 diseases with the most similar symptoms are displayed.

📝 Example Input
```
fever, headache, muscle pain
```
💡 Output
```
Possible Diseases:
Dengue
Flu
COVID-19
```
📁 Dataset
The symptom-disease mapping is hardcoded in a simple pandas DataFrame for demonstration purposes. You can expand it by adding more diseases and symptom patterns.






