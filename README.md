# zeotap2
An online assignment for campus recruitment process.
# CDP ChatBot: Your Query Assistant

Welcome to the **CDP Co-Pilot** project! This web application fetches detailed answers from Segment, mParticle, Lytics, and Zeotap documentation to assist with Customer Data Platforms (CDP) queries.

## Overview

CDP Co-Pilot is designed to be a helpful assistant that answers queries related to CDP documentation. It uses natural language processing techniques to understand and fetch the most relevant information from multiple sources. The application is built with efficiency in mind, ensuring quick and accurate responses to user queries.

## Features

- Fetch detailed answers from Segment, mParticle, Lytics, and Zeotap documentation.
- Compare answers across all sources.
- Preprocess text to improve the accuracy of results.
- Cache results for improved efficiency.

## Tech Stack

The tech stack for this project includes:

1. **Streamlit**: Used for building the web interface. Streamlit is an open-source app framework that allows for creating and sharing beautiful, custom web apps for machine learning and data science.

2. **Requests**: A simple and elegant HTTP library for Python, used to make HTTP requests to fetch documentation pages.

3. **BeautifulSoup**: A library for web scraping purposes to pull the data out of HTML and XML files. It is used to parse the fetched documentation pages.

4. **Sentence-Transformers**: A Python framework for state-of-the-art sentence, text, and image embeddings. It is used to encode the queries and documentation text into embeddings for similarity comparison.

5. **Torch**: An open-source machine learning library used in conjunction with Sentence-Transformers for handling tensor operations and similarity calculations.

6. **Re**: Python’s built-in library for regular expressions, used for tokenizing text.

7. **Scikit-learn (sklearn)**: A machine learning library for Python, used to remove stopwords from the text.

## Data Structures

1. **Dictionaries**:
   - **`docs_links`**: A dictionary that maps CDP names to their respective documentation links.
   - **`results`**: A dictionary used to store the answers fetched from different CDP sources for comparative purposes.

2. **Lists**:
   - **Paragraphs**: Lists used to store the parsed paragraphs from the documentation pages.
   - **Filtered tokens**: Lists used to store the tokens after preprocessing the text.

3. **Tensors**:
   - Used in Sentence-Transformers to encode the queries and documents into embeddings.

## Why These Choices

- **Streamlit**: Chosen for its simplicity and rapid development capabilities. It allows for easy creation of interactive web applications.
- **Requests and BeautifulSoup**: Essential for web scraping, making it possible to fetch and parse documentation from web pages.
- **Sentence-Transformers and Torch**: Provide powerful NLP capabilities, enabling the application to understand and process natural language queries effectively.
- **Re and Sklearn**: Used for efficient text preprocessing, including tokenization and stopword removal.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/cdp-co-pilot.git
   cd cdp-co-pilot
