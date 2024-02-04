# chatwithpdf
Chat with PDFs
This Streamlit app allows users to chat with PDF documents. It uses language processing techniques to extract text from PDFs and provide conversational responses to user questions based on the content of the PDFs.

# Features
Upload multiple PDF files.
Enter a question related to the content of the PDF files.
Receive conversational responses based on the question and the content of the PDF files.
How to Use
Upload PDF Files: Use the file uploader in the sidebar to upload one or more PDF files containing the content you want to chat about.

Ask a Question: In the main section of the app, enter a question related to the content of the uploaded PDF files in the text input box labeled "Ask a Question from the PDF Files".

Submit & Process: Click on the "Submit & Process" button. This will initiate the processing of the uploaded PDF files.

View Response: After processing, the app will display a response to your question based on the content of the PDF files.

# Installation
To run this Streamlit app locally, follow these steps:

Clone this GitHub repository:

Copy code
git clone https://github.com/your-username/your-repository.git

Navigate to the project directory:
Copy code
cd your-repository

Install the required Python packages:
Copy code
pip install -r requirements.txt

Set up the necessary environment variables. Make sure to obtain a Google API key and add it to your environment variables.

Run the Streamlit app:
Copy code
streamlit run app.py

Access the app in your web browser at http://localhost:8501.

# Dependencies
Streamlit
PyPDF2
langchain
langchain_google_genai
dotenv

# License
This project is licensed under the MIT License. See the LICENSE file for details.

