# 📰 Fake News Detector

This Jupyter Notebook project uses machine learning to classify news as **Fake** or **Real** based on the content. It includes a fully interactive interface built using `ipywidgets`.

## 🧠 Technologies Used

- Python 3
- Jupyter Notebook
- pandas, scikit-learn
- TF-IDF vectorization
- Logistic Regression
- ipywidgets for UI

## 📁 Dataset

Dataset used: [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)  
A sample CSV version is loaded directly from GitHub in the notebook for ease of use.

## 🚀 How It Works

1. The dataset is cleaned and labeled (`REAL` = 1, `FAKE` = 0)
2. Text is vectorized using TF-IDF
3. A Logistic Regression model is trained
4. An interactive textbox lets users input custom text to classify

## 🧪 How to Use

1. Open the `Fake_News_Detector.ipynb` file in Jupyter Notebook
2. Run all cells
3. Paste any news text or headline into the text area
4. Click **Classify** to get a prediction: 🟢 Real News or 🔴 Fake News

## 📸 Demo

You can add a GIF or screenshot here after running the notebook.

## 🔧 Setup

Install dependencies with:

```bash
pip install pandas scikit-learn ipywidgets
jupyter nbextension enable --py widgetsnbextension
