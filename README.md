# Final Project: Artificial Intelligence - AI School Hol7 (Modares Sejjadi Haddadi)

This repository contains the final projects for the Artificial Intelligence course at Modares saji Haddadi's AI class, helli7. The projects were developed as part of the curriculum with a deadline at the end of the Khordad examinations.

## Project Overview

This project encompasses three main areas within Artificial Intelligence:

1.  **E-commerce Product Classification:** Developing a classification model for products on the Digikala e-commerce platform. The model is trained and served using PyTorch, TorchServe, and a FastAPI application for seamless integration and prediction.
2.  **Stock Market Index Prediction:** Building a time-series forecasting model to predict the closing price of a stock market index. The model utilizes OHLCV data and optionally incorporates other technical indicators for enhanced accuracy.
3.  **Khayyam's Poetry Generation (Optional):** An experimental project using Recurrent Neural Networks (RNNs) to generate poetry in the style of Omar Khayyam. The model learns to predict the second couplet of a quatrain based on the first couplet.

## Technologies Used

*   **Programming Language:** Python
*   **Machine Learning Frameworks:** PyTorch, TensorFlow/Keras (optional, depending on model choice)
*   **Serving:** TorchServe, FastAPI
*   **Data Handling & Analysis:** Pandas, NumPy
*   **Web Scraping (if applicable):** BeautifulSoup, Scrapy
*   **Financial Data:** yfinance (for stock data)
*   **NLP Libraries:** NLTK, SpaCy, Transformers

## Setup and Installation

*(This section would detail how to set up the environment, install dependencies, and run each project. It would typically include steps like:*
*   *Cloning the repository*
*   *Creating a virtual environment*
*   *Specific instructions for each project (e.g., data download, model training commands, running servers).*
*   *Example commands for running the FastAPI/TorchServe applications.)*

## Project Details

### 1. Digikala Product Classification

*   **Objective:** Classify Digikala products into relevant categories.
*   **Methodology:**
    *   Data collection and preprocessing of product descriptions.
    *   Training a text classification model (e.g., using BERT or other NLP models) with PyTorch.
    *   Serving the model with TorchServe.
    *   Exposing predictions via a FastAPI endpoint.
*   **Key Files:** `digikala_classifier`, `torchserve_config/`, `fastapi_app/`, `data/`

### 2. Stock Market Index Prediction

*   **Objective:** Predict the closing price of a stock market index.
*   **Methodology:**
    *   Acquisition of historical OHLCV data.
    *   Feature engineering including technical indicators (e.g., Moving Averages, RSI).
    *   Training a time-series forecasting model (e.g., LSTM, GRU).
    *   Evaluation using standard metrics.
*   **Key Files:** `stock_predictor`, `data/`

### 3. Khayyam's Poetry Generation (Optional)

*   **Objective:** Generate quatrains in the style of Omar Khayyam.
*   **Methodology:**
    *   Collecting and cleaning Khayyam's poetry.
    *   Building an RNN (LSTM/GRU) based encoder-decoder model.
    *   Training the model on first-second couplet pairs.
    *   Implementing text generation.
*   **Key Files:** `khayyam_poet/`, `data/`

## Authors

*   **Course:** Artificial Intelligence
*   **School:** Helli7
*   **Instructor:**  Modares: sajji Haddadi(my love❤️)
*   **Students:** [tahou elahibakhsh]


