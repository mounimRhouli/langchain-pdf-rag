# RAG - LangChain, OpenAI, OpenAI Embeddings, ChromaDB (Vector Database), Docker

A Streamlit-based application that allows users to upload **PDF documents** and ask questions about their content.

## Prerequisites

You must have Docker installed on your machine.

## Steps

1. **Clone this repository.**
2. **Rename** `.env.example` **to** `.env` and add your `OPENAI_API_KEY`.
3. **Build and start the services:**

```bash
docker-compose up --build
```

If this command doesn't work, use the following commands instead:

```bash
docker-compose down -v
docker-compose build --no-cache
docker-compose up -d
```

4. Open the Streamlit frontend at [http://localhost:8501](http://localhost:8501).  
   The backend will be running at [http://localhost:8000](http://localhost:8000).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
