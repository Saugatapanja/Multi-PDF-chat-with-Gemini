# Multi-PDF-chat-with-Gemini
Introduction:
The MultiPDF Chat App is a Python application that lets you interact with several PDF documents simultaneously. You can pose questions about the content of the PDFs in natural language, and the app will generate appropriate responses based on the information within the documents. It uses a language model to provide accurate answers to your questions. Keep in mind that the app will only respond to queries related to the PDFs that have been loaded.

How It Works

![image](https://github.com/user-attachments/assets/3a815b77-6e31-4b8f-b0d5-fe3e3379165c)

The application uses the following process to answer your questions:

PDF Loading: The app processes multiple PDF documents and extracts the text from them.

Text Chunking: The extracted text is broken down into smaller, manageable segments.

Language Model: The app utilizes a language model to create vector representations (embeddings) of these text segments.

Similarity Matching: When a question is asked, the app compares it with the text segments to find the ones most relevant in terms of meaning.

Response Generation: The chosen text segments are then used by the language model to generate a response based on the relevant information from the PDFs.

![image](https://github.com/user-attachments/assets/2914aa9e-0d9b-432b-981b-79f9d34af9f6)
