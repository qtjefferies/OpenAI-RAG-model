# OpenAI-Stock-RAG-Model

## Overview
The OpenAI-Stock-RAG-Model is a project that leverages OpenAI's Retrieval-Augmented Generation (RAG) model to analyze and predict stock  trends. This model combines the power of retrieval-based methods with generative capabilities to provide insightful and accurate feedback of stock information based on key financial metrics from yahoo finance.

## Features
- **Data Retrieval**: Efficiently retrieves relevant stock market data from yfinance API.
- **Generative Analysis**: Uses advanced generative models to analyze trends based on the price and financials.
- **Prediction Accuracy**: High accuracy in predicting stock information.

## Requirements
- **API Key**: You will need to create a .env file and insert your own API key in the `.env` file to run this project using the OPENAP_API_KEY variable.

## Installation
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage
To use the model, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/qtjefferies/OpenAI-Stock-RAG-Model.git
    ```
2. Navigate to the project directory:
    ```bash
    cd OpenAI-Stock-RAG-Model
    ```
3. Run the main script:
    ```bash
    python main.py
    ```

## Acknowledgements
- OpenAI for their powerful models and APIs.
- Contributors and the open-source community.
