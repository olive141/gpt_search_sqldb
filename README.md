# Use Azure OpenAI and LangChain to Chat with SQL Data

## installation

If you use viual code this helps create virtual environment : https://code.visualstudio.com/docs/python/python-tutorial#_create-a-virtual-environment

To get started, before running the notebook in this repo, install LangChain with the following command:

pip install langchain

## Environment Setup

Using LangChain will usually require integrations with one or more model providers, data stores, apis, etc.

pip install openai

this is schema of config.json that you need to add to project
{ 
    "OPENAI_API_BASE":"https://yours.openai.azure.com/",
    "OPENAI_API_KEY":"your key"
}

