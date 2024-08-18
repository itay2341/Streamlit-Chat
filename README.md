# Chat with Multiple PDFs

This project is a Streamlit-based web application that allows users to upload multiple PDF documents and interact with them via a chatbot interface. The application processes the PDFs, extracts their text, splits the text into manageable chunks, and uses OpenAI's language model to facilitate conversational retrieval of information from the documents.

## Features

- **Upload PDFs:** Upload one or multiple PDF files to the application.
- **Text Extraction:** Extracts text from the uploaded PDFs.
- **Text Chunking:** Splits the extracted text into smaller chunks for efficient processing.
- **Conversational Retrieval:** Use a chatbot to ask questions about the contents of the PDFs.
- **Persistent Chat History:** Maintains a history of the conversation for better context management.

## Installation

### Prerequisites

- Python 3.7 or higher
- Streamlit
- OpenAI API Key
- PyPDF2
- dotenv

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/itay2341/Streamlit-Chat.git
   cd chat-with-pdfs

    ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install the required packages:**

   ```bash
    pip install -r requirements.txt
    ```

4. **Set up the environment variables:**

   Create a `.env` file in the root directory of the project and add the following variables:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

5. **Run the Streamlit application:**

   ```bash 
    streamlit run app.py
    ```

## Usage

1. **Upload PDFs:**

   Click on the "Upload PDFs" button to select one or multiple PDF files from your local machine.

2. **Process Documents:**

    After uploading, click the "Process" button to extract and prepare the text for querying.

3. **Ask Questions**

    Use the chatbot interface to ask questions about the contents of the PDFs. The application will use OpenAI's language model to generate responses based on the extracted text.

4. **View Chat History**
    
        The chat history will be displayed on the right side of the screen, allowing you to keep track of the conversation.

