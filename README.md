# Sentiment Analysis Dashboard

An interactive Streamlit-based dashboard that performs sentiment analysis on Amazon customer reviews using Natural Language Processing (NLP). The application combines VADER sentiment analysis with emoji-based sentiment detection to provide deeper insights into customer feedback.

## Features

### Sentiment Breakdown
- Analyze customer reviews using VADER Sentiment Analyzer.
- Visualize sentiment distribution with interactive pie charts.

### Word Cloud Visualization
- Generate a word cloud from customer reviews.
- Identify frequently used words and trends.

### Keyword Search
- Search reviews using custom keywords.
- Quickly find customer opinions related to specific topics.

### Filtered Comments
- Filter reviews by:
  - Positive
  - Negative
  - Neutral sentiments

### Sentiment Timeline
- Track sentiment trends over time.
- Monthly sentiment analysis visualization.

### Emoji-Based Sentiment Analysis
- Detect emojis from reviews.
- Classify sentiments based on emoji usage.
- Compare text sentiment with emoji sentiment.

### Sentiment Summary
- Generate overall sentiment statistics.
- Display sentiment percentages and dominant sentiment.

### Report Generator
- Create downloadable Word reports (.docx).
- Include:
  - Sentiment Breakdown
  - Word Cloud
  - Timeline Charts
  - Emoji Analysis
  - Summary Statistics
  - Sample Comments

---

## Technologies Used

- Python
- Streamlit
- Pandas
- Plotly
- NLTK (VADER Sentiment Analysis)
- WordCloud
- Emoji
- Python-Docx
- Plotly Express

---

## Project Structure

```
project/
│
├── app.py
├── amazon_reviews.csv
├── requirements.txt
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/sentiment-analysis-dashboard.git
cd sentiment-analysis-dashboard
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## Dataset

The dashboard uses Amazon customer review data containing:

- Reviewer Name
- Review Text
- Review Date
- Customer Feedback

Dataset file:

```text
amazon_reviews.csv
```

---

## Sentiment Analysis Methodology

### VADER Sentiment Scoring

Classification Rules:

| Compound Score | Sentiment |
|---------------|-----------|
| ≥ 0.05 | Positive |
| ≤ -0.05 | Negative |
| Otherwise | Neutral |

### Emoji Sentiment Detection

Supported emojis:

| Emoji | Sentiment |
|--------|-----------|
| 😊 | Positive |
| 😍 | Positive |
| 👍 | Positive |
| 😢 | Negative |
| 😡 | Negative |
| 👎 | Negative |
| 😐 | Neutral |

A hybrid sentiment approach combines textual sentiment and emoji sentiment for enhanced interpretation.

---

## Dashboard Preview

Features included:

- Sentiment Pie Chart
- Word Cloud
- Keyword Search
- Review Filtering
- Timeline Analysis
- Emoji Sentiment Insights
- Report Export Functionality

---

## Future Enhancements

- Machine Learning-based sentiment models
- Real-time review ingestion
- Product-wise analysis
- Customer segmentation
- Advanced NLP insights
- PDF report generation
- Deployment on Streamlit Cloud

---

##  Author

**Kavya S**

Data Analytics & AI Enthusiast

GitHub: https://github.com/Kavya061206

---

