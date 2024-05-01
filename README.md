# Chat with Your PDF

This application allows users to interact with the text content of their PDF documents through a conversational interface. Users can ask questions related to the content of the uploaded PDF files, and the application will provide relevant answers using a conversational retrieval chain.
## Video :

Check out the video [here](https://www.youtube.com/watch?v=W2_z6CTmme8) to learn how to use the application.

## Features:

- **PDF Text Extraction**: The application extracts text content from uploaded PDF documents.
- **Conversational Interface**: Users can ask questions based on the content of the PDF files.
- **Real-time Responses**: The application provides real-time responses to user queries.

## How to Use:

1. **Upload PDF Documents**: Click on the "Upload your PDF Files" button in the sidebar and select the PDF files you want to interact with.
2. **Process**: Click on the "Process" button to extract text content from the uploaded PDF files and initialize the conversational interface.
3. **Ask Questions**: Type your questions related to the PDF content in the text input field.
4. **View Responses**: The application will display the user's question and the corresponding bot answer in real-time.

## Dependencies:

- **Streamlit**: Streamlit is used to build the web application interface.
- **PyPDF2**: PyPDF2 library is utilized for reading PDF files.
- **FAISS**: FAISS is used as the vector database for storing and retrieving text embeddings efficiently.
- **OLLMA (On-Device Large Language Model Access)**: OLLMA is a language model that enables efficient language understanding and generation tasks on-device.
- **langchain**: langchain is a library that provides various natural language processing functionalities, including text splitting, vector storage, and conversational retrieval.

## Setup:

1. Clone the repository:
   ```
   git clone https://github.com/vikash-64/ChatWithPdf.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the application:
   ```
   streamlit run app.py
   ```


Feel free to contribute, report issues, or suggest improvements!
