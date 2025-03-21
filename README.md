# RAG System

A customizable RAG (Retrieval-Augmented Generation) system that allows you to create AI-powered applications based on your own data.

## Features

- Document processing from multiple sources (.pdf, .txt, .md, .docx)
- Vector storage with MongoDB
- AI-powered chat interface
- Multiple model support (Google Gemma, Microsoft Phi-3)

## Installation

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/rag-system.git
cd rag-system

# Create and activate virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install the package in development mode
pip install -e .
```

## Usage

Check the example code in `app.py` to see how to use the RAG system.

## Project Structure

- `rag/` - Core package files
- `data/` - Data storage directory
- `app.py` - Example application
- `query.py` - Query processing utilities
- `chat.py` - Chat interface

## License

MIT

## Credits

Originally based on the Scogo RAG system, modified for personal use. 