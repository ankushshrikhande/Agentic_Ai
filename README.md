[README.md](https://github.com/user-attachments/files/26105907/README.md)
# 🧠 Embeddings & NLP Fundamentals

A collection of Jupyter notebooks and resources exploring core NLP concepts including text splitting, embeddings, HuggingFace models, and data validation with Pydantic.

---

## 📁 Repository Structure

| File | Topic | Description |
|------|-------|-------------|
| `2.2.1 RecursiveTextSplitter.ipynb` | Text Splitter | Demonstrates LangChain's `RecursiveCharacterTextSplitter` for chunking large text documents into manageable pieces |
| `2.3.1-embeddings.ipynb` | Embeddings | Introduction to text embeddings — converting text into dense vector representations for semantic understanding |
| `2.3.2-hugginface.ipynb` | Embeddings | Using HuggingFace models to generate embeddings; exploring pre-trained transformer models |
| `pydantic.ipynb` | Pydantic | Data validation and settings management using Pydantic models in Python |
| `speech.txt` | Embeddings | Sample text data used for embedding and NLP experiments |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed, then install the required packages:

```bash
pip install langchain openai huggingface-hub sentence-transformers pydantic jupyter
```

### Running the Notebooks

1. Clone this repository:
   ```bash
   git clone https://github.com/ankushshrikhande/<repo-name>.git
   cd <repo-name>
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

3. Open any `.ipynb` file and run the cells in order.

---

## 📦 Dependencies

| Package | Purpose |
|--------|---------|
| `langchain` | Text splitting utilities |
| `openai` | OpenAI embedding models |
| `sentence-transformers` | HuggingFace sentence embedding models |
| `huggingface-hub` | Access to pre-trained HuggingFace models |
| `pydantic` | Data validation and schema enforcement |
| `jupyter` | Interactive notebook environment |

---

## 📚 Topics Covered

- **Text Splitting** — Recursively splitting documents while preserving semantic context
- **Text Embeddings** — Transforming natural language into vector space representations
- **HuggingFace Integration** — Loading and using transformer-based embedding models
- **Pydantic Validation** — Structuring and validating data for LLM pipelines
- **Speech/Text Data** — Working with raw text samples for NLP tasks

---

## 🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests if you'd like to contribute or suggest improvements.

---

## 👤 Author

**Ankush Shrikhande**  
GitHub: [@ankushshrikhande](https://github.com/ankushshrikhande)
