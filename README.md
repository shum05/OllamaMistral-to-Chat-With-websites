# Ollama-Mistral-to-Chat-With-Websites

This Chainlit application enables interaction with website URLs through advanced natural language processing capabilities.

### Features
```
- **Ollama and Mistral**: Utilizes Ollama AI with the Mistral model, offering robust language understanding and generation capabilities.
- **LangChain Framework**: Powered by LangChain, a Python framework for integrating and deploying language models.
- **Chainlit Deployment**: Integrated with Chainlit for seamless deployment and interaction.
```
## System Requirements

- Python 3.9 or later installed.

---

## Steps to Replicate 

```
# Clone the Repository
git clone [https://github.com/shum05/OllamaMistral-to-Chat-With-websites.git]
cd OllamaMistral-to-Chat-With-websites

# Set Up Environment Variables
# Obtain necessary environment variables from LangSmith website.
cat <<EOF > .env
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
LANGCHAIN_API_KEY="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"
LANGCHAIN_PROJECT="OllamaMistral_project"
EOF

# Create and Activate Virtual Environment (On Windows)
python -m venv ollama-mistral-env
.\ollama-mistral-env\Scripts\Activate.ps1

<<<<<<< HEAD
# Install Required Python Packages
pip install -r requirements.txt

# Pull the Mistral Model
ollama pull mistral

# Run Data Ingestion
python ingest.py

# Launch the Chat UI
chainlit run main.py
```
=======
5. Run the following command in your terminal to start the chat UI:
   ```
   python3 ingest.py #for ingesting
   chainlit run main.py #for chainlit ui
```
>>>>>>> 5f0604bebf031c45737b13cc7cb0995b092c3932
