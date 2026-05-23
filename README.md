## Overview

This project demonstrates deep learning sequence modeling using Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, Gated Recurrent Units (GRUs), and Bidirectional LSTM architectures for sentiment analysis and sequential text learning.

Using the TensorFlow/Keras IMDB Reviews dataset, the project explores preprocessing, sequence vectorization, model experimentation, comparative evaluation, and optimization techniques for natural language processing (NLP) workflows.
---
## Technologies Used

### Programming Language
- Python

### Deep Learning Libraries
- TensorFlow
- Keras

### Data Science Libraries
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
---
# Deep-Learning-RNN-LSTM-Sequence-Modeling
Deep learning sequence modeling system using RNN and LSTM architectures for temporal prediction, sequential learning, and advanced neural network analysis.
---
## Visualizations

### Sequence Length Distribution

Illustrates IMDB review length analysis used to determine sequence truncation and padding strategy.

![Sequence Length Distribution](visuals/sequence_length_distribution.png)

### Model Comparison Results

Comparison of RNN, LSTM, GRU, stacked LSTM, and bidirectional LSTM architectures using validation accuracy and loss metrics.

![Model Comparison Results](visuals/model_comparison_results.png)
---
## Dataset

This project uses the TensorFlow/Keras IMDB Reviews dataset for sentiment sequence modeling.

Dataset source:

```python
tensorflow.keras.datasets.imdb
```

The dataset is downloaded programmatically during notebook execution; therefore no local dataset files are required in the repository.
---

## Final Model Performance

Best Performing Model: **LSTM_BI_1X (Bidirectional LSTM)**

- Validation Accuracy: **87.40%**
- Validation Loss: **0.3931**
- Dataset: IMDB Reviews
- Sequence Length: 256
- Task: Binary Sentiment Classification
## Repository Structure

```text
Deep-Learning-RNN-LSTM-Sequence-Modeling/
│
├── notebooks/
│   └── RNN LSTM For Sequence Modeling.ipynb
│
├── visuals/
│   ├── sequence_length_distribution.png
│   └── model_comparison_results.png
│
├── data/
│   └── .gitkeep
├── README.md
└── requirements.txt
```
---
## Installation & Execution

Clone repository:

```bash
git clone https://github.com/Dare215/Deep-Learning-RNN-LSTM-Sequence-Modeling.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```
---
## Future Improvements

Future enhancements may include:

- Increase training epochs and perform hyperparameter tuning to improve validation accuracy.
- Add pretrained word embeddings such as GloVe or Word2Vec for richer text representation.
- Compare LSTM performance against transformer-based models such as BERT.
- Add confusion matrix, precision, recall, and F1-score for deeper classification evaluation.
- Deploy the best-performing model in a Streamlit sentiment analysis web app.
- Add explainability methods to identify which words or phrases most influence predictions.
- Test the model on additional text datasets to evaluate generalization.
- Optimize the model for faster inference and lower memory usage.
---
## Author

### Darious Brown  
PhD Candidate — Artificial Intelligence & Machine Learning

Areas of Interest:
- Deep Learning
- Sequence Modeling
- Natural Language Processing (NLP)
- Predictive Analytics
- Biotech AI Applications
- AI-Driven Operational Intelligence

Portfolio:  
https://dare215.github.io/DariousBrown-Portfolio/

LinkedIn:  
https://www.linkedin.com/in/dariousbrown
