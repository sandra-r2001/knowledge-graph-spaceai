# knowledge-graph-spaceai
Assignment for SPACEAI: Knowledge Graph Builder using embeddings and Neo4j
# Knowledge Graph Builder - SPACEAI Task

## Objective
This script takes short text inputs, generates embeddings using HuggingFace (alternative to OpenAI due to quota limits), stores them in a Neo4j graph database, and performs a similarity query.

## Files Included
- `main.ipynb` — Jupyter Notebook with full code
- `neo4j_dashboard.png` — Screenshot of Neo4j showing 3 text nodes
- `output_sample.png` — Screenshot of similarity query output
- `requirements.txt` — Python dependencies

## Notes
- Neo4j AuraDB Free tier was used.
- Embeddings generated using `sentence-transformers/all-MiniLM-L6-v2`.


### Tools Used
- Python 3.11+
- Hugging Face (Sentence Transformers)
- Neo4j Aura Free

### What it does
- Embeds text using a transformer model
- Stores nodes with embeddings in Neo4j
- Runs cosine similarity to find related texts

### Sample Output
See output.png for similarity query results.
See neo4j_screenshot.png for graph structure.
