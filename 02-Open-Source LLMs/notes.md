### Notes for using Ollama for QA in a Streamlit UI 

- Create docker-compose.yaml file and run the following command in terminal to containarize elasticsearch and ollama
```
    docker-compose -up
```
- Install streamlit 

```
    pip install streamlit  
```
- Run  streamlit app:
```
    streamlit run qa_faq.py
```
Note: Make sure documents are already indexed in elasticsearch! For example:

```
for doc in documents:
    es_client.index(index=index_name, document=doc)
```
