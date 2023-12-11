# 🚀 Navigator and Insight Extractor

This repository contains the code and resources for an AI-powered document navigator and insight extractor. The focus of this readme is specifically on the machine learning (ML) part of the system.

## 🌐 Overview
The AI-powered document navigator and insight extractor is designed to simplify the understanding of regulatory documents. It leverages technologies such as OpenAI's ChatGPT, LangChain, and ChromaDB to create a user-friendly chatbot interface capable of navigating, interpreting, and extracting insights from complex regulatory documents.

## 📋 Task performed

### 1. Web Scraping Tasks

With this web scraping project, I performed the following three main tasks:

1. **📄 Document Extraction:** This involved extracting all documents from websites, including PDF documents, and extracting text from them. Additionally, I extracted text from images saved within PDF files.

2. **📊 PDFs to Excel:** I saved the extracted PDFs into an Excel format. This step facilitates the project owner's ability to review the documents and determine if they match the ones on their websites.

3. **🔍 Text Extraction and Categorization:** I extracted text from websites across all pages and categorized them based on relevant criteria.

4. **📝 Metadata Creation:** I generated metadata for each document and web page.

*Note*: To execute this code without errors, it's recommended to use Kaggle or Google Colab and run the entire script from the beginning, as certain libraries may need to be installed and configured.

Develop AI model and train it on preprocessed data.

## 2. 🧠 Machine Learning Technologies

The machine learning component of this project incorporates various technologies to enhance document navigation and insight extraction.

### 🛠️ Technologies Used

1. **OpenAI GPT-4:**
   - *Reason:* GPT-4 is chosen for its state-of-the-art natural language processing capabilities. It excels in understanding context, making it suitable for conversational AI and question-answering applications.

2. **LangChain:**
   - *Reason:* LangChain provides a versatile set of tools for handling embeddings, text splitting, vector stores, and conversational chains. Its modular design allows for flexibility in building and customizing language models.

3. **Chroma (Vector Store):**
   - *Reason:* Chroma is selected as the vector store for its efficiency in storage and retrieval of vectors. It plays a crucial role in enabling fast and accurate document retrieval, contributing to the overall responsiveness of the system.

4. **Flask:**
   - *Reason:* Flask is a lightweight and easy-to-use web framework, making it ideal for building the API. Its simplicity and scalability align with the project's requirements for serving machine learning models via HTTP endpoints.

5. **Tiktoken:**
   - *Reason:* Tiktoken is employed for counting tokens in a text, which is essential for managing usage and staying within API limits when interacting with OpenAI's language model.

6. **Werkzeug:**
   - *Reason:* Werkzeug is used as a WSGI utility library, providing essential tools for building web applications. It complements Flask and enhances the project's capabilities for handling HTTP requests.

7. **OpenAI Python SDK:**
   - *Reason:* The OpenAI Python SDK is utilized as a convenient client for interacting with the OpenAI API. It simplifies integration with the GPT-4 model, enabling seamless communication between the application and the language model.

## 📑 Additional Details

- **System Template:**
  - *Reason:* The custom system message template is designed to guide responses, ensuring coherent and contextually appropriate answers in the conversation.

- **Data Source:**
  - *Reason:* The knowledge base is loaded from a JSON file named `all_scraped_data.json`, providing a structured and pre-existing set of information for the model to reference.

- **Vector Store Persistence:**
  - *Reason:* Vector data is persisted in the `./rdb_knowledge_base` directory, enabling efficient storage and retrieval of document vectors for improved performance.
 
## 3. 🛠️ Installation and Usage Instructions

### Web Scraping Part

#### Installation:

1. **Install Web Scraping Libraries (Jupyter Notebook):**
    ```python
    !pip install BeautifulSoup4 --quiet
    !pip install requests --quiet
    !pip install pdf2image --quiet
    !pip install --upgrade certifi --quiet
    !pip install python-docx --quiet
    !pip install urllib3==1.26.6  --quiet
    !pip install pdf2image --quiet
    !pip install easyocr --quiet
    !pip install PyMuPDF
    ```

### Running the Web Scraping Code:

2. **Execute Web Scraping Code:**
   Execute the provided web scraping code in your Jupyter Notebook.
   
### Machine Learning Part

#### Installation:

3. **Create Virtual Environment (Optional):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
    ```

4. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application:

5. **Run Flask Application:**
    ```bash
    python your_ml_app.py
    ```
   Replace `your_ml_app.py` with your actual Flask application script.

## 🌟 Conclusion

These instructions guide you through setting up and running the machine learning and web scraping components of the application. Make sure to follow each step to ensure a smooth experience. If you encounter any issues, refer to the documentation or seek assistance from the project team.

Note: Ensure you have the necessary permissions to install packages and run scripts on your environment.
