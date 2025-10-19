# tapssp-project
CSC 363 Final Project
For my final project I want to make a command-line Rust tool that indexes your local documents, finds the most relevant pieces for a user's question, and augments the question with those pieces when calling a large language model (LLM) for higher quality answers.

The user adds local documents (e.g., .txt, .md, or converted .pdf files).
The system processes and embeds these documents.
When the user asks a question, the tool:
Searches the stored document embeddings
Retrieves the most relevant chunks
Sends the query plus relevant context to an LLM
Returns a grounded, context-aware answer
