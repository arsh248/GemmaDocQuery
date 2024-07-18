# GemmaDocQuery

This application provides an end-to-end document question-and-answer system using Google Gemma, integrated with Streamlit.

<img width="1512" alt="Screenshot 2024-07-18 at 6 57 28 PM" src="https://github.com/user-attachments/assets/6c36dd70-acc1-4631-ab39-ca7ac6b71458">


## Setup

1. **Environment Setup:**
   - Ensure you have Python installed.
   - Install required packages listed in `requirements.txt`.
   - Create a `.env` file and add your API keys:
     ```
     GROQ_API_KEY=your_groq_api_key
     GOOGLE_API_KEY=your_google_api_key
     ```

2. **Running the Application:**
   - Run `streamlit run app.py` in your terminal.
   - Access the application at `http://localhost:8501` (or another URL specified by Streamlit).

## Functionality

### Features:
- **Document Embedding:** Embeds documents using Google Generative AI Embeddings and FAISS.
- **Question Answering:** Answers user questions based on embedded documents.
- **Document Similarity Search:** Allows exploration of similar documents based on user queries.

### Components:
- **Streamlit Interface:** Provides a user-friendly interface for inputting questions and displaying results.
- **LangChain Integration:** Utilizes LangChain for document processing, including document splitting and chaining.

## Usage

1. Enter your question in the text input field.
2. Click "Documents Embedding" to initialize document embeddings (if not already done).
3. View the answer to your question and explore similar documents using the expandable "Document Similarity Search" section.

