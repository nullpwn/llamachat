## Retrieval Augmented Generation (RAG)


### Setup
1. git clone https://github.com/nullpwn/llamachat.git
2. cd llamachat
3. pip install -r requirements.txt
4. Install Ollama (https://ollama.com/download)
5. ollama pull llama3 (etc)
6. ollama pull mxbai-embed-large
7. python upload.py (pdf, .txt, JSON)
8. python localrag.py (with query re-write)
9. python localrag_no_rewrite.py (no query re-write)

### Email RAG Setup
1. git clone https://github.com/nullpwn/llamachat.git
2. cd llamachat
3. pip install -r requirements.txt
4. Install Ollama (https://ollama.com/download)
5. ollama pull llama3 (etc)
6. ollama pull mxbai-embed-large
7. set YOUR email logins in .env (for gmail create app password)
9. python collect_emails.py to download your emails
10. python emailrag2.py to talk to your emails

 

### What is RAG?
RAG is a way to enhance the capabilities of LLMs by combining their powerful language understanding with targeted retrieval of relevant information from external sources often with using embeddings in vector databases, leading to more accurate, trustworthy, and versatile AI-powered applications

### What is Ollama?
Ollama is an open-source platform that simplifies the process of running powerful LLMs locally on your own machine, giving users more control and flexibility in their AI projects. https://www.ollama.com
