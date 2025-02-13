# Stock_Trend_Analyzer
Develop a predictive model to forecast stock price movements using historical data. Analyze data with Python and create a Streamlit app

## 🚀 Features

- **Utilizes LangChain** for structured and efficient AI-driven search.
- **FAISS (Facebook AI Similarity Search)** for fast vector-based retrieval.
- **OpenAI's Embeddings** to convert text into dense vectors.
- **Streamlit-based UI** for interactive searching.
- **FastAPI backend** for API-based access.

- ---

## 📌 Architecture Overview

### 🔹 LangChain Model
The project integrates **LangChain**, a powerful framework for building applications with LLMs.  
📌 *Below is a visual representation of how LangChain connects various components:*  

![LangChain Model](./LangChainModel.png)

### 🔹 Retrieval Process
The retrieval process involves **embedding documents** and searching using **FAISS**. The diagram below explains how queries are processed to fetch relevant results efficiently.  

![Retrieval Process](./Retrieval.png)

### 🔹 UI Interaction
Users interact with the system through a **Streamlit UI**, where they can enter queries and receive AI-powered results.  
📌 *Below is a preview of the UI:*  

![UI Screenshot](./Screenshot%20(169).png)

---
##  Set Up Environment Variables
Create a .env file and add your OpenAI API key:
```bash
OPENAI_API_KEY=your_openai_api_key
```
## Run the Streamlit App
```bash
streamlit run app.py
```
## 🛠 Usage
Enter Stock Symbol: Input a stock ticker (e.g., AAPL, TSLA).
Select Date Range: Choose historical data for analysis.
View Trend Predictions: The model predicts future price movements.
Compare Trends: Analyze past patterns and projected trends.

## ⚡ Tech Stack
- **Python** - Data processing & analysis.
- **LangChain** - AI workflow orchestration.
- **FAISS** - Efficient stock data retrieval.
- **OpenAI** Embeddings - Converts stock-related data into numerical representations.
- **FastAPI** - Backend API handling requests.
- **Streamlit** - Interactive user interface.

## 🎯 Contributions
Contributions are welcome! Feel free to fork this repo, make changes, and submit a pull request. 😃
