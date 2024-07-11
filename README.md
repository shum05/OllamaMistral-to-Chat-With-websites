# Ollama-Mistral-to-Chat-With-Websites
Simple Chainlit app to have interaction with website URLs.

### Chat with your documents 🚀
- [Ollama](https://ollama.ai/) and `mistral` as llm
- [LangChain](https://python.langchain.com/en/latest/modules/models/llms/integrations/huggingface_hub.html) as a Framework for LLM
- [Chainlit](https://docs.chainlit.io/) for deploying.

## System Requirements

must have Python 3.9 or later installed. 

---

## Steps to Replicate 

1. Clone it locally.
```
git clone [https://github.com/shum05/OllamaMistral-to-Chat-With-websites.git]
cd OllamaMistral-to-Chat-With-websites
```

2. take the environment variables from [LangSmith](https://smith.langchain.com/) website
   
3. Create a virtualenv and activate it
   ```
   python3 -m venv .venv && source .venv/bin/activate
   ```

4. Run the following command in the terminal to install necessary python packages:
   ```
   pip install -r requirements.txt
   ```

5. Run the following command in your terminal to start the chat UI:
   python3 ingest.py #for ingesting
   chainlit run main.py #for chainlit ui
```
