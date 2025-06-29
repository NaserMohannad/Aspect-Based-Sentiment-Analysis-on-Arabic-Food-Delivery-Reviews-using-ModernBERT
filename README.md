# Aspect-Based Sentiment Analysis for Arabic Food Delivery Reviews using ModernBERT

This project applies a transformer-based language model (ModernBERT) to perform **Aspect-Based Sentiment Analysis (ABSA)** on Arabic food delivery reviews. It includes three subtasks:

1. **Aspect Term Detection (T1)** – Identify the aspect terms in the sentence.
2. **Aspect Category Classification (T2)** – Classify each term into one of the predefined categories (Service, Price, Time, Location).
3. **Aspect Polarity Classification (T3)** – Detect whether the sentiment is Positive or Negative.

## 🧠 Dataset
- Custom dataset collected from Arabic tweets related to food delivery.
- Includes 4 aspect categories and over 23,000 labeled aspects.
- The data is provided in `All_data.xlsx`.

## 🧪 Models
- We use a **ModernBERT-based NER model** for joint classification of aspect and category.
- A separate classifier is used for **aspect polarity**.

## 🧩 Files
- `assignment-2.ipynb`: Main notebook for training ModernBERT on ABSA tasks.
- `All_data.xlsx`: Excel file containing annotated tweets.
- `3TALLIP.pdf`: Reference research paper.

## 🚀 How to Run
1. Open the notebook in Jupyter or Google Colab.
2. Follow the instructions and run all cells in order.

## 📊 Evaluation
Models are evaluated using:
- **F1-Score**
- **Accuracy**
- **Precision & Recall**

---

