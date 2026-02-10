# Agentic-RAG-Pipeline

LLM struggle with remaining up to date and being trained on current data.  RAG poses a solution to this problem.

Retrieval-Augmented Generation optimizes the output of LLMs by referring to knowledge outside of training data to retrieve relevant information before generating a response.  RAG enhances LLM output.

## RAG

The following presents the building blocks of a RAG system:

 - External Data

 - Retrieve Relevant Info

 - Augment Prompt to LLM

## Agentic RAG

Instead of just pulling additional data from the Vector DB and using that as context for the prompt to the LLM, Agentic RAG adds additional layers of feedback.  The LLM is used to determine the data retrieval decisions.