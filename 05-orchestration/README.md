# Data Preparation in RAG using MAGE

## Getting started

1. Clone [repository](https://github.com/ozgeozge/rag-project.git)
```bash
git clone https://github.com/ozgeozge/rag-project.git
cd rag-project
```
3. navigate to the `rag-project/llm` directory, add `spacy` to the requirements.txt.
4. Then update the `Dockerfile` found in the `rag-project` directory with the following:
```YAML
RUN python -m spacy download en_core_web_sm
```
4. Run

```bash
`./scripts/start.sh`
```

Once started, go to [http://localhost:6789/](http://localhost:6789/)
