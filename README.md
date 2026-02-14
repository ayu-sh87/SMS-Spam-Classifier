# SMS/Email Spam Classifier

A machine learning–powered web application that detects whether a message is **Spam** or **Not Spam (Ham)**.  
The system uses Natural Language Processing (NLP) techniques and a Naive Bayes classifier to make real-time predictions through an interactive Streamlit interface.

---

##  Features

- Real-time spam prediction
- Clean and interactive Streamlit UI
- Confidence score display
- Message statistics (word & character count)
- TF-IDF based text vectorization
- Lightweight and fast model

---

## Machine Learning Pipeline

1. Text preprocessing
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Stemming
2. Feature extraction using **TF-IDF Vectorizer**
3. Model training using **Multinomial Naive Bayes**
4. Real-time prediction via Streamlit app

---

##  Tech Stack

- Python
- Scikit-learn
- NLTK
- Streamlit
- Pandas
- NumPy

---

##  Project Structure

sms-spam-classifier/
│
├── app.py # Streamlit web app
├── model.pkl # Trained spam detection model
├── vectorizer.pkl # TF-IDF vectorizer
├── spam.csv # Dataset
├── README.md


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier

2. Install dependencies
pip install -r requirements.txt

3. Download NLTK data
import nltk
nltk.download('punkt')
nltk.download('stopwords')

4. Run the app
streamlit run app.py

Model Performance

Algorithm: Multinomial Naive Bayes
Accuracy: ~97–98%
Precision: ~99% for spam detection
(Values may vary depending on preprocessing and dataset split.)

📸 Screenshots
screenshots is in the above section

 Use Cases

Email spam filtering
SMS filtering systems
NLP learning projects
Internship demonstrations

👨‍💻 Author
Ayush Singh
Machine Learning & AI Enthusiast
GitHub: [https://github.com/your-username](https://github.com/ayu-sh87/SMS-Spam-Classifier
LinkedIn: www.linkedin.com/in/ayu108

📄 License
This project is for educational and demonstration purposes.

