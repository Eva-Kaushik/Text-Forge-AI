# TextForgeAI

## Overview
This repository amalgamates web scraping and OpenAI GPT-3.5 Turbo, providing a robust Python script for automated information extraction, summarization, and question-answering from web pages within a specified domain.

## Business Use-Case
Ideal for businesses and developers seeking automated, domain-specific information extraction and content understanding. The integration with OpenAI GPT-3.5 Turbo enhances the capability to generate concise summaries and answer questions based on the collected textual data.

## Requirements
- Python 3.x
- OpenAI GPT-3.5 Turbo API key
- Libraries: `openai`, `urllib`, `requests`, `re`, `bs4`, `deque`, `urlparse`, `HTMLParser`, `os`, `pandas`, `numpy`, `tiktoken`

## Software/Tools/Packages
- **OpenAI GPT-3.5 Turbo:** Empowers natural language understanding and generation.
- **Pandas:** For efficient data manipulation with DataFrames.
- **Beautiful Soup (bs4):** Enables HTML parsing for web scraping.
- **tiktoken:** Facilitates token counting in text strings.
- **Urllib and Requests:** Essential for URL handling and HTTP requests.

## Usage
1. **API Key Setup:**
   - Acquire your OpenAI GPT-3.5 Turbo API key.
   - Configure the API key within the script.

2. **Configuration:**
   - Customize the `domain` variable to specify the target root domain.

3. **Run the Script:**
   ```bash
   python script.py


Web Scraping
The script employs web scraping techniques to collect textual content from a specified domain. It establishes a structured directory to store raw text files and performs essential text processing for subsequent analysis.

OpenAI Integration
Upon extracting and processing the text, the script leverages OpenAI GPT-3.5 Turbo to generate concise summaries and provide answers to questions based on the scraped content. Dedicated functions are included for creating context and responding to questions using the OpenAI API.

## Result
The output of the script includes:

Raw scraped data stored in CSV format (processed/scraped.csv).
Processed text embeddings stored in CSV format (processed/embeddings.csv).
Feel free to tailor the script to suit your specific requirements and use cases.

## Acknowledgments
This project is made possible by the capabilities provided by OpenAI. Special thanks to the contributors and maintainers of the libraries used in this project.

