CDP Query Assistant
Overview
The CDP Query Assistant is a web-based chatbot developed using Streamlit that provides information and documentation insights for various Customer Data Platforms (CDPs) such as Segment, mParticle, Lytics, and Zeotap. It enables users to search for detailed documentation, retrieve relevant sections, and even perform comparisons across different platforms.

Key Features:
Documentation Scraping: Automatically fetches documentation links and relevant sections from official CDP sites.
Semantic Search: Leverages sentence-transformers to generate and match text embeddings, ensuring accurate and meaningful search results.
Cross-CDP Comparison: Users can compare functionalities and documentation across different CDPs.
User Interaction & Chat History: Streamlit provides a user-friendly interface with text input and history tracking for seamless user engagement.
Technologies Used:
Streamlit: Used for building the interactive web application.
BeautifulSoup: A web scraping library to parse and extract documentation links from HTML pages.
requests: To handle HTTP requests for fetching content from external documentation pages.
sentence-transformers: A library that generates text embeddings to perform semantic search.
torch: Backend support for tensor computations and similarity measures.
Setup Instructions:
Prerequisites:
Python 3.x installed on your system.
streamlit, requests, beautifulsoup4, sentence-transformers, torch packages installed.
Installation:
Clone the repository:

bash
git clone https://github.com/yourusername/CDP-Query-Assistant.git
cd CDP-Query-Assistant
Create a virtual environment:

bash
python -m venv env
source env/bin/activate  # On Windows use: `env\Scripts\activate`
Install the required packages:

bash
pip install -r requirements.txt
Run the Streamlit application:

bash
streamlit run app.py
Usage:
Querying: Input your query into the text field. The chatbot will retrieve the most relevant documentation or information from the selected CDP.
Cross-CDP Comparison: Enable the comparison mode to select two CDPs and view their functionalities side by side.
Contributing:
Contributions to this project are welcome! If you find any issues or would like to add new features, please fork the repository, make your changes, and submit a pull request.

License:
This project is licensed under the MIT License.

Contact:
For any queries or suggestions, feel free to reach out to:

Author: Prashanth K T
