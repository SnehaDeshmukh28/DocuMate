# DocuMate

DocuMate is an advanced Retrieval-Augmented Generation (RAG) application built with Streamlit, enabling users to upload multiple documents and engage in interactive chat sessions. The application leverages state-of-the-art NLP models from Hugging Face and Ollama for document understanding and response generation, maintaining a chat history for a seamless conversation flow.

## Features

- **Document Upload**: Upload multiple PDF documents to the application.
- **Interactive Chat**: Ask questions related to the uploaded documents and receive relevant responses.
- **Chat History**: Track previous interactions to maintain context.
- **Advanced NLP**: Utilizes Hugging Face models (Instructor and Flan-T5) and Ollama embeddings for document understanding and response generation.
- **User-Friendly Interface**: Streamlit-based UI for intuitive user experience.

## Getting Started

### Prerequisites

- Python 3.7+
- pip (Python package installer)
- Git

## Technologies Used

- **Streamlit**: Python library for building interactive web applications.
- **Hugging Face**: Utilized for NLP models such as Instructor and Flan-T5.
- **Ollama**: Open-source platform for running large language models (LLMs) locally on your machine.
- **Llama3**: Latest version of Meta's large language model, integrated for conversational retrieval.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/SnehaDeshmukh28/DocuMate.git
   cd DocuMate
   ```

2. **Setup Virtual Environment**:

   ```bash
   python -m venv venv
   # Activate virtual environment
   venv\Scripts\activate   # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```

3. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

1. **Start the Streamlit Server**:

   ```bash
   streamlit run app.py
   ```

2. **Access the Application**:

   Open your web browser and navigate to `http://localhost:8501` to interact with DocuMate.

## Contributing

We welcome contributions to enhance DocuMate! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Contact

For questions or suggestions, feel free to contact us at [deshmusn@gmail.com](mailto:deshmusn@gmail.com).
