# 📈 Stock Market Sentiment Analysis & NER System

An AI-powered financial text analysis system that performs:

- Sentiment Analysis on stock market statements
- Named Entity Recognition (NER) for financial entities
- Stock, Crypto, and Market Index identification
- Market opinion classification using OpenAI GPT

---

## 🚀 Features

### Sentiment Analysis
Classifies financial statements into:

- Bullish (Positive)
- Bearish (Negative)
- Neutral

Using OpenAI GPT models trained through prompt engineering.

### Named Entity Recognition (NER)

Extracts important market-related entities such as:

- Stocks
- Companies
- Market Indices
- Cryptocurrencies
- Organizations

Examples:

- Apple
- Google
- Microsoft
- Tesla
- NASDAQ
- Dow Jones
- S&P 500
- Bitcoin
- Ethereum

---

## 🛠 Technologies Used

- Python
- OpenAI API
- spaCy
- NLP
- GPT-3.5 Turbo

---

## 📂 Project Structure

```text
MarketAnalysis.ipynb
│
├── OpenAI Sentiment Analysis
├── spaCy Named Entity Recognition
├── Financial Entity Extraction
└── User Input Processing
```

---

## ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Stock-Market-Sentiment-Analysis-NER.git
cd Stock-Market-Sentiment-Analysis-NER
```

### Install Dependencies

```bash
pip install openai==0.28
pip install spacy
```

### Download spaCy Model

```bash
python -m spacy download en_core_web_sm
```

---

## 🔑 Configure OpenAI API Key

Set your API key securely using environment variables.

Linux/Mac:

```bash
export OPENAI_API_KEY="your_api_key"
```

Windows:

```cmd
set OPENAI_API_KEY=your_api_key
```

---

## ▶ Usage

Run the notebook or Python script.

Example:

```text
Enter the category:
Stock

Enter your market statement:
Tesla stock is expected to rise significantly next quarter.
```

Output:

```text
Sentiment Analysis Result:
Positive (Bullish)

Identified Market Entities:
[('Tesla', 'ORG')]
```

---

## 📊 Example Categories

- Stock
- Index
- Crypto
- Economy
- Other

---

## 🎯 Applications

- Stock Market Research
- Financial News Analysis
- Investor Sentiment Tracking
- Market Intelligence
- Cryptocurrency Analysis
- Financial NLP Research

---

## 🔮 Future Improvements

- Real-time market news integration
- Stock price prediction support
- Financial dashboard
- Streamlit web application
- Multiple language support
- Advanced financial NER model

---

## 🤝 Contributing

Contributions are welcome.

Fork the repository and submit a pull request with improvements.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed as an NLP and Financial Sentiment Analysis project using OpenAI GPT and spaCy.
