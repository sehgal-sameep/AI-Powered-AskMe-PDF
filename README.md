
<h1 align="center" style="font-weight: bold;">AI-Powered: AskMe PDF 💻</h1>

<p align="center">
<a href="#features">Features</a>
<a href="#technologies">Tech Stack</a>
<a href="#started">Getting Started</a>
<a href="#flow">Process Flow Diagram</a>
<a href="#routes">API Endpoints</a>
</p>


<p align="center">AI-Powered: AskMePDF is a Java-based project that enables users to upload PDF documents and ask questions about the content through an API endpoint. The project leverages Retrieval Augmented Generation (RAG) to provide accurate and context-aware answers based on the information within the uploaded PDF.</p>


<p align="center">
<a href="https://drive.google.com/file/d/1vjecVww96PLkJ1UpZ4Z_ny8ZOB-_V0a-/view?usp=sharing">📱 Watch Demo</a>
</p>

<h2 id="features">💻 Key Features</h2>

- PDF Upload and Processing: Users can upload PDF documents, and the application will extract the content for querying.
- Question-Answering API: An API endpoint allows users to ask questions related to the uploaded document, retrieving precise answers based on the context.
- Powered by GPT-3.5 Turbo: Utilizes OpenAI's GPT-3.5 Turbo for generating human-like responses, integrating the powerful capabilities of LLMs for language understanding.
- Vector DB Integration: Data is stored and retrieved from AstraDB (a Datastax product), using vector embeddings for semantic similarity and effective information retrieval.
- Embeddings and LangChain4j: Incorporates LangChain4j for handling text embeddings and chaining LLM tasks, enhancing the precision and relevance of responses.
- Efficient Learning: Students and teachers can use AskMePDF for fast knowledge retrieval, improving learning and growth by getting precise answers without scanning through entire documents.
- Time Saving: The RAG model ensures that queries are answered in seconds, enabling users to focus on learning and productivity instead of time-consuming searches.

<h2 id="technologies">💻 Tech Stack</h2>

- Language: Java
- Machine Learning Model: GPT-3.5 Turbo (via OpenAI API)
- Database: AstraDB (Datastax Vector Database)
- Libraries: LangChain4j (for embeddings and model interaction)
- Frameworks: Spring Boot for API endpoints


<h2 id="started">🚀 Getting started</h2>

1) Clone the repository.
```bash
git clone https://github.com/sehgal-sameep/AI-Powered-AskMe-PDF.git
```
2) Install required dependencies.
3) Configure the OpenAI API key and AstraDB credentials in the environment.
4) Run the project using Java/Spring Boot.

<h2 id="flow">🚀 Understanding Flow</h2>
<p align="left">
<a href="https://drive.google.com/file/d/1FykkbpVpJqqxtowyMh9vbKE6Ao0OVfKY/view?usp=sharing"> Process Flow Diagram</a>
</p>


<h2 id="routes">📍 API Endpoints</h2>


| route               | description                                          
|----------------------|-----------------------------------------------------
| <kbd>POST /api/chat</kbd>     | send query to model 




<h3> 📍 Documentations that might help</h3>

[💻 Video Recorded Demo](https://drive.google.com/file/d/1vjecVww96PLkJ1UpZ4Z_ny8ZOB-_V0a-/view?usp=sharing)

[📝 Langchain4j](https://docs.langchain4j.dev/get-started)


