# QueryAssist

QueryAssist is a Streamlit application that provides a streamlined workflow for leveraging the power of OpenAI's Student ChatGPT and retrieving information from study notes.

## Application Workflow

The QueryAssist application provides a streamlined workflow for leveraging the power of OpenAI's Student ChatGPT and retrieving information from study notes:

### Adding Study Notes URLs

- In the sidebar, you can add up to three URLs for study notes by entering the URLs in the text input fields.

- After adding the URLs, click the "Process URLs" button. This initiates data loading and processing.

### Asking Questions

- In the main section, use the "Question" input field to enter your queries.

- Press Enter after entering your question, and the application will provide answers based on the processed data.

### Viewing Sources

- If available, the application will display sources used to generate the answer in a "Sources" section.

## Special Terms and Concepts

To effectively use the QueryAssist application, it's important to understand the following terms and concepts:

- **OpenAI API**: This application leverages the OpenAI API to interact with a Student ChatGPT. You must obtain an OpenAI API key to use this feature.

- **FAISS**: A powerful library used for efficient similarity search and retrieval of data. The application uses FAISS to index and retrieve relevant information from documents.

- **Streamlit**: A Python library designed for creating web applications with minimal code. It serves as the framework for building the user interface of this application.

- **Langchain**: Langchain is a component of this application that assists in various language processing tasks, such as document splitting, embedding creation, and vector storage management.

