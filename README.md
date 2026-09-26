# Azure Document Chat Assistant

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)

A Flask application that demonstrates retrieval-augmented chat over documents stored in Azure Blob Storage and indexed with Azure AI Search. It combines retrieved passages with an OpenAI model to answer questions about the connected content.

## Setup

Install the dependencies from `app/requirements.txt` and configure the Azure Storage, Azure AI Search, and OpenAI settings through environment variables. The example values in `app/app.py` are placeholders and must be replaced with your own service configuration.

The project is an integration sample and requires the corresponding Azure resources and credentials before it can serve useful answers.
