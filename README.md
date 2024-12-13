# Content Engine: Comparative Analysis of Financial Reports

This project allows users to analyze and compare Form 10-K filings from multinational companies (Alphabet Inc., Tesla Inc., and Uber Technologies Inc.). The system extracts key insights, compares numbers, and answers user queries using RAG techniques.

## Technologies Used
- Python 3.x
- Hugging Face Transformers
- Sentence Transformers
- PyTorch
- Gradio

## Features
- Extracts content from financial documents (Form 10-K)
- Compares data across multiple documents
- Allows users to ask queries about specific sections of the documents
- Built-in chatbot interface for ease of interaction

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Satvik-jain/Assignment-Alemeno.git
   cd Assignment-Alemeno
   
2. Set up a virtual environment:
   ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/macOS
    venv\Scripts\activate     # For Windows
   
3. Install the dependencies:
    ```bash
      pip install -r requirements.txt

4. Setting up Pinecone API:
   First, Go to app.pinecone.io and get an API key, Then add that API to your enviornment.

   Create a .env file then write and save this
   ```bash
   PINECONE_API_KEY = <your api key>
   ```
   Now, run the notebook and confirm that ```load_dotenv()``` is running before pinecone inititation
   
   
## Example Usage
Query 1: "Compare the revenue between Alphabet Inc. and Tesla in 2021"

Query 2: "Highlight the major differences in liabilities between Uber and Alphabet"
