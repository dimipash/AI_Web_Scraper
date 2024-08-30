# AI Web Scraper

An intelligent web scraping tool that uses Streamlit, Selenium, and LangChain to extract and parse website content based on user-defined criteria.

## Features

-   Web scraping with Selenium
-   Content parsing with LLM (Ollama)
-   User-friendly interface with Streamlit

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/dimipash/AI_Web_Scraper.git
    cd ai-web-scraper
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Download the appropriate [ChromeDriver](https://developer.chrome.com/docs/chromedriver/downloads#chromedriver_1140573590) for your system and put it in the root directory.

4. Install and run Ollama:
    - Follow the installation instructions for Ollama from the [official website](https://ollama.ai/).
    - Once installed, run the following command to download and start the required model:
        ```
        ollama run llama3.1
        ```

## Usage

1. Ensure the Ollama 3.1 model is running locally.

2. Run the Streamlit app:

    ```
    streamlit run main.py
    ```

3. Enter a website URL and click "Scrape site".
4. Describe the information you want to extract and click "Parse Content".

## Requirements

See `requirements.txt` for a full list of dependencies.
