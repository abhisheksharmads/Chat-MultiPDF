# MultiPDF Chat App: Interactive Querying for Multiple PDFs

## Introduction
The MultiPDF Chat App is an intuitive Python-based solution that enables real-time, natural language interactions with multiple PDF documents. Built on cutting-edge language model technology, this application offers precise answers to your questions based on the content within the loaded PDF files. Please note that the application specializes in answering questions specifically related to the content of the PDFs you have loaded.

## How the App Functions
The MultiPDF Chat App employs a multi-step approach to deliver accurate and relevant responses:

1. **PDF Loading**: The application ingests multiple PDF files and extracts the textual content for analysis.
  
2. **Text Segmentation**: The extracted text is then segmented into manageable chunks to facilitate efficient processing.

3. **Textual Analysis via Language Model**: These text chunks are processed through a language model to create vector embeddings that encapsulate their semantic content.

4. **Semantic Matching**: Upon receiving a query, the application performs a semantic similarity comparison between the query and the available text chunks.

5. **Intelligent Response Generation**: The semantically relevant text chunks are fed back into the language model, which then formulates an appropriate response based on the PDF content.

## Dependencies and Setup Instructions
To get started with the MultiPDF Chat App, please adhere to the following setup steps:

1. Clone the repository onto your local machine.

2. Navigate to the project directory and install the necessary dependencies using the following command:
    ```bash
    pip install -r requirements.txt
    ```

3. Acquire an API key from OpenAI and populate the `.env` file in your project directory accordingly.
    ```bash
    OPENAI_API_KEY=your_secret_api_key_here
    ```

## How to Use
Here’s how you can interact with the MultiPDF Chat App:

1. Make sure that all dependencies are installed and that the OpenAI API key is added to your `.env` file.

2. Launch the application by executing the following command in your terminal:
    ```bash
    streamlit run app.py
    ```

3. This will open the application in your default web browser, showcasing the user interface.

4. Follow the on-screen prompts to upload multiple PDF documents into the application.

5. Utilize the chat interface to ask questions in natural language pertaining to the content within the loaded PDFs.

## License
The MultiPDF Chat App is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
