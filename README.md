# 💳 Credit Card Fraud Detection with Imbalanced Learning

A machine learning project that tackles the challenge of detecting fraudulent credit card transactions in highly imbalanced datasets. Using SMOTE (Synthetic Minority Over-sampling Technique) and ensemble methods, this model achieves **high recall on fraud detection** while maintaining overall accuracy—critical for protecting financial institutions and their customers.

---

## 🎯 Business Impact

- **Problem**: Only 0.17% of transactions are fraudulent, making traditional ML models biased toward the majority class
- **Solution**: Implements imbalanced learning techniques to dramatically improve fraud detection rates
- **Result**: A production-ready model that catches more fraud while minimizing false positives

---

## 📚 Project Documentation

| Audience | Document |
|----------|----------|
| **Non-Technical** | [Executive Summary](summary_report.md) — Key findings and business insights |
| **Technical** | [Analysis Notebook](analysis.ipynb) — Full code, models, and visualizations |

---

## 🛠️ Tools & Technologies

- **Python 3.x**
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-learn
- **Imbalanced Learning**: SMOTE, class weighting
- **Environment**: Jupyter Notebook

---

## 📊 Dataset

The [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) contains:
- **284,807** transactions over 2 days
- **492** fraudulent cases (0.17%)
- **31 features** including PCA-transformed variables (V1-V28), Time, and Amount

**Download the dataset**: [creditcard.csv](https://media.geeksforgeeks.org/wp-content/uploads/20240904104950/creditcard.csv)

After downloading, place the `creditcard.csv` file in the project root directory.

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/Rashad1019/imbalanced-learn.git
cd imbalanced-learn

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate  # Windows
# source .venv/bin/activate  # macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook analysis.ipynb
```

---

## 📬 Contact

**Rashad Ferguson**  
📧 [Rashad19@outlook.com](mailto:Rashad19@outlook.com)  
🔗 [GitHub](https://github.com/Rashad1019)

---

*Built with ❤️ for the data science community*
