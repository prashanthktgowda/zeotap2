# CDP Query Assistant

## **Overview**  
The **CDP Query Assistant** is a web-based chatbot built using **Streamlit**, designed to provide documentation insights and comparison capabilities for various **Customer Data Platforms (CDPs)**, including **Segment**, **mParticle**, **Lytics**, and **Zeotap**. The application allows users to search for detailed documentation, retrieve relevant content, and perform cross-platform comparisons seamlessly.

## **Key Features**:
- **Documentation Scraping**: Automatically extracts documentation links and key sections from official CDP documentation websites.
- **Semantic Search**: Utilizes **sentence-transformers** to generate text embeddings and perform accurate, context-based search using cosine similarity.
- **Cross-CDP Comparison**: Provides the ability to compare CDP functionalities side by side for better understanding and decision-making.
- **User Interaction & Chat History**: Streamlit offers a user-friendly interface with text input and a persistent chat history to keep track of past queries and responses.

## **Technologies Used**:
- **Streamlit**: A simple yet powerful framework for building interactive web applications quickly.
- **BeautifulSoup**: An HTML parser library used for scraping documentation links from official websites.
- **requests**: A simple and elegant library for making HTTP requests to fetch content from web pages.
- **sentence-transformers**: A library for generating sentence embeddings, enabling semantic similarity comparisons.
- **torch**: A powerful deep learning library that supports tensor computations used for text embeddings and similarity calculations.

## **Setup Instructions**:

### **Prerequisites**:
- Python 3.x installed on your system.
- Required libraries (`streamlit`, `requests`, `beautifulsoup4`, `sentence-transformers`, `torch`) installed.

### **Installation**:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CDP-Query-Assistant.git
   cd CDP-Query-Assistant
