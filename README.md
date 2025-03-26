## Saber AI Doc Scraper

### Your Intelligent Document Assistant powered by Streamlit and Ollama

---

### Overview

Saber AI Doc Scraper is a powerful yet intuitive tool leveraging cutting-edge NLP technology to quickly analyze, index, and query information directly from PDF documents. Built with Streamlit for ease of use, Saber AI effortlessly extracts meaningful insights using advanced semantic search and Large Language Models (LLMs).

---

### Features

- **Easy PDF Upload:** Instantly upload and process research papers, reports, or any PDF documents.
- **Semantic Search:** Quickly locate relevant sections within lengthy documents.
- **Context-Aware Q&A:** Obtain concise, factual answers based on document context, powered by a fine-tuned Ollama LLM (`deepseek-r1:1.5b`).
- **Responsive Interface:** Smooth, visually appealing UI featuring custom dark-mode styling for comfortable reading.
- **Interactive Chat:** Engage naturally with your documents through conversational Q&A.

---

### Technologies Used

- **Streamlit:** Interactive web application framework for rapid development.
- **LangChain:** Toolkit for robust document processing, embeddings, and LLM integration.
- **Ollama Embeddings:** Efficient, local vector embeddings for fast semantic retrieval.
- **Ollama LLM (`deepseek-r1:1.5b`):** Lightweight yet powerful language model delivering accurate and contextually relevant responses.
- **PDFPlumber:** Precise PDF parsing and text extraction.

---

### Installation & Usage

**Clone the repository:**

```bash
git clone [repository_link]
cd saber-ai-doc-scraper
```

**Install dependencies:**

```bash
pip install -r requirements.txt
```

**Run the application:**

```bash
streamlit run rag_deep.py
```

Open your browser and navigate to `http://localhost:8501` to use the application.

---

### Workflow

1. Upload your PDF document using the intuitive interface.
2. Saber AI processes and indexes document content using semantic embeddings.
3. Ask questions directly related to the document.
4. Instantly receive concise, contextually accurate answers.

---

### Future Enhancements

- Batch document upload support.
- Advanced analytics for deeper document insights.
- Integration with additional LLM models.

---

### Contributions

Feedback and contributions are warmly welcomed! Feel free to submit issues or pull requests to enhance this tool.

