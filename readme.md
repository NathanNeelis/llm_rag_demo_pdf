# DEMO Large Language Models RAG

This repository contains a jupyternotebook file which contains a working RAG demo.

## setup

1. You need to setup a opensearch database locally. I prefer using Docker.
2. You need an OpenAI apikey which some credits on it.

## In this demo

0. Setup
1. Connect to Opensearch
2. Connec to OpenAI
3. Create an index in the Opensearch database
4. Extraxt text from the PDF
5. Chunk the text
6. Generate embeddings (from the chunks)
7. Index the chunks
8. Experiment with kNN results
9. Write a query
10. Get the top 5 results (Retrieval step)
11. Build the context for the LLM (Augmentation step)
12. Prompt the LLM (Generation step)

## Future work

The following list is what comes to mind:

1. Add more then 1 document
2. Add and use metadata. From which source comes your information?
3. Upgrade code to python functions
4. build a pipeline
