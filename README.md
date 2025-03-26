**Saber AI Doc Scraper**

**Your Intelligent Document Assistant powered by Streamlit and Ollama**

Overview:

Saber AI Doc Scraper is a powerful yet intuitive tool that leverages cutting-edge NLP technology to help you quickly analyze, index, and query information directly from your PDF documents. Built with Streamlit for a user-friendly experience, Saber AI allows users to effortlessly extract meaningful insights using advanced semantic search and Large Language Models (LLMs).

Features

Easy PDF Upload: Instantly upload and process research papers, reports, or any PDF document.

Semantic Search: Quickly find relevant sections within lengthy documents.

Context-Aware Q&A: Get concise and factual answers based on document context using a fine-tuned Ollama LLM (deepseek-r1:1.5b).

Responsive Interface: Smooth, visually appealing UI with custom dark-mode styling for comfortable reading.

Interactive Chat: Engage naturally with your documents through conversational Q&A.

Technologies Used

Streamlit: Interactive web app framework for rapid application development.

LangChain: Robust toolkit for document processing, embeddings, and LLM integration.

Ollama Embeddings: Efficient, local vector embeddings for rapid semantic retrieval.

Ollama LLM (deepseek-r1:1.5b): Lightweight yet powerful language model for accurate and contextually relevant responses.

PDFPlumber: Precise PDF parsing and text extraction.

Installation & Usage

Clone the repository:

git clone [repository_link]
cd saber-ai-doc-scraper

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

Navigate to http://localhost:8501 in your browser to access the app.

Workflow

Upload a PDF document through the user-friendly interface.

Saber AI processes and indexes the content using semantic embeddings.

Ask questions directly about the document contents.

Receive concise, contextually accurate answers instantly.

Future Enhancements

Support for batch document uploads.

Advanced analytics for document insights.

Integration with additional LLM models for varied use cases.

Contributions

Contributions and feedback are welcome! Feel free to submit issues or pull requests to help improve this tool.

