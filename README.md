# FlanT5-PDFChat

FlanT5-PDFChat is a conversational AI system built using Google's FLAN-T5 model, customized to process and interact with uploaded PDF documents. This project enables users to upload a PDF file and chat with an AI that provides answers strictly based on the document's content.

## Features
- ✅ Upload and process PDF files
- ✅ Extract text content and ensure accurate information retrieval
- ✅ Chat and ask questions based only on the uploaded document
- ✅ Uses FLAN-T5 for natural language responses
- ✅ Prevents hallucination by restricting knowledge to the provided PDF

## Installation
Ensure you have Python installed, then install the required dependencies:

```sh
pip install langchain
pip install sentence-transformers
pip install torch transformers
pip install pypdf
```

## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/Myusuf121/FlanT5-PDFChat.git
   cd FlanT5-PDFChat
   ```

2. Run the script or Jupyter Notebook to start the chatbot:
   ```sh
   jupyter notebook
   ```

3. Upload a PDF file and start asking questions based on its content.

## Model Details
This implementation uses:
- **FLAN-T5 (Base, Large, or XXL versions)** for generating text responses
- **Sentence Transformers (all-mpnet-base-v2)** for embedding-based retrieval

## Future Improvements
- Support for multi-PDF uploads
- Improved UI for interaction
- Integration with vector databases for enhanced retrieval

## License
This project is open-source and available under the MIT License.

---

🚀 *Contributions and suggestions are welcome!*

