# PDF-Question-Answering-APP

## Project Description

This project aims to provide a user-friendly web interface for extracting contents from PDF documents and allowing users to ask questions about the content. The application leverages Streamlit for the frontend and integrates with a language model (LLM) for question-answering capabilities.

Users can upload a PDF document, and the application will extract texts from it. The extracted texts are then passed to a pre-trained language model for question-answering. This enables users to pose natural language questions about the content of the PDF and receive relevant answers.

The primary technologies used in this project include Streamlit for building the web interface, PyMuPDF for PDF processing, and an LLM for natural language understanding and question-answering.

## Objectives

1. **Table Extraction:** Develop a robust mechanism for extracting contents from PDF documents, ensuring accuracy and maintaining the structure of the original tables.

2. **Question-Answering Interface:** Implement an intuitive interface that allows users to ask questions about the content of the PDF. Leverage a pre-trained language model to generate accurate responses.

3. **Streamlit Integration:** Utilize the Streamlit framework to create a seamless and responsive web interface. Ensure a user-friendly experience for both table extraction and question-answering functionalities.

4. **Dockerization:** Containerize the application using Docker to facilitate easy deployment and scalability. This allows users to run the application in a consistent environment across different platforms.

5. **Deployment on Render:** Prepare the application for deployment on Render, a cloud platform for hosting and managing web applications. Provide instructions for users to deploy the application effortlessly.

6. **Documentation:** Create comprehensive documentation, including a README file, to guide users on how to use the application, upload PDFs, ask questions, and interpret the results.

7. **User-Friendly Experience:** Prioritize a clean and intuitive user interface. Ensure that users, even with minimal technical knowledge, can navigate the application seamlessly.

8. **Scalability and Performance:** Optimize the application for performance and scalability to handle varying document sizes and user traffic.

## How to Use

1. Clone the repository to your local machine.
2. Create a virtual environment using Python's `venv` or conda.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run the Streamlit application with `streamlit run app.py`.
5. Access the application at the provided URL.


---