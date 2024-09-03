# AI-RAG

# Full-Tutorial by @lunaxoniichan
Summarize: https://www.youtube.com/watch?v=_K0lRd-4LpM&t=1s

How to Get-Start: https://www.youtube.com/live/z5kH4tCDgMA?si=yOyzSHH3MCXqaLge

# Requirements
1) Docker
2) Conda: Python3.10

# Get-Start
1) clone repo
2) Put your llm model in model/ (download it from huggingface)
3) install torch: https://pytorch.org/get-started/locally/
4) pip install -r requirements.txt

# VectorDB (Postgres)
## How to use
1) docker-compose up -d
2) docker exec -it vector_store psql -U admin -d vector_store

## Commands
Show databases: 
> \d

# Chatbot UI
RUN
> chainlit run chatbot.py -w
