# Data Science Project: PDF Information Retrieval App

This repository contains the code for a data science project that develops an app to take a PDF document as input, process its details, and save the information as embeddings in the Pinecone vector database. The information is then retrieved by the OpenAI GPT-3 language model, specifically the Davinci model, based on the query asked by the user.

## Project Overview

The app is designed to extract and process the details from PDF documents, convert them into embeddings, and store them in the Pinecone vector database. The OpenAI GPT-3 language model, Davinci, is used to retrieve relevant information based on user queries. The project involves the integration of various technologies and tools, including PDF processing libraries, Pinecone for vector storage, and OpenAI's GPT-3 API.

## Repository Contents

The repository contains the following key files and directories:

- `app.py`: The main application file responsible for processing PDF documents, generating embeddings, and interfacing with Pinecone and the OpenAI GPT-3 API.
- `requirements.txt`: A file listing all the dependencies and libraries required to run the application.
- `data/`: A directory containing sample PDF documents for testing and development purposes.
- `README.md`: The readme file providing an overview of the project and instructions for running the application.

## Getting Started

To run the PDF Information Retrieval App, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Ensure you have valid API keys for Pinecone and OpenAI GPT-3, and update the corresponding credentials in the `app.py` file.
4. Run the `app.py` file to start the application.

## Contributions

Contributions to the project are welcome. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
