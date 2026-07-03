# 📋 Online Exam Auto-Evaluator with AI Detection

An AI-powered web application that automatically evaluates student answers by comparing them with a model answer key. It uses keyword matching, TF-IDF, and BERT-based semantic similarity to generate scores and provides AI-written text detection and performance analysis.

## ✨ Features

* Automatic extraction of questions and answers
* AI-based answer evaluation
* Keyword, TF-IDF, and BERT similarity scoring
* Strict, Balanced, and Lenient grading modes
* Question-wise score breakdown
* Automatic percentage and grade calculation
* AI-generated text detection
* Student performance statistics
* Strength and weakness analysis
* Downloadable CSV reports
* Interactive Streamlit interface

## 🛠️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Sentence Transformers
* BERT
* NLTK
* Hugging Face Transformers
* RapidFuzz

## 🚀 Installation

1. Clone the repository:

```bash
git clone <your-repository-url>
cd <project-folder>
```

2. Install the required dependencies:

```bash
pip install streamlit numpy pandas scikit-learn sentence-transformers nltk transformers torch rapidfuzz
```

3. Run the application:

```bash
streamlit run app.py
```

## 📖 How to Use

1. Paste the model answer key with question numbers and marks.
2. Enter the student’s name, ID, and answers.
3. Select the desired grading strictness.
4. Click **Evaluate Exam** to generate results.
5. View question-wise scores, grades, and performance statistics.
6. Run AI detection to identify potentially AI-generated answers.
7. Download the final evaluation report as a CSV file.

## 🧠 Evaluation Method

The system evaluates answers using a weighted combination of:

* **Keyword Matching** – Checks important keyword overlap.
* **TF-IDF Similarity** – Measures textual similarity.
* **BERT Semantic Similarity** – Compares the meaning and context of answers.

The final score depends on the selected grading mode: **Strict**, **Balanced**, or **Lenient**.

## 📊 Output

The application provides:

* Total marks obtained
* Overall percentage
* Final grade
* Question-wise marks
* Keyword, TF-IDF, and BERT scores
* AI-generation probability
* Performance statistics
* Strength and weakness analysis
* Downloadable CSV report

## ⚠️ Disclaimer

AI-generated text detection should be used only as an indicator and not as definitive proof. Automated evaluation results should be reviewed by teachers for important academic decisions.

## 👨‍💻 Project Type

**AI / Machine Learning / Natural Language Processing / Education Technology**
