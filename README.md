# Medicine Chatbot

Medicine Chatbot is a chatbot application designed to provide users with medical information, offer details about medications, and answer medical-related questions. This project leverages modern natural language processing (NLP) and machine learning tools to deliver an efficient and accurate information retrieval experience.

## Features

- **Text-Based Q&A System**: Enables users to ask medical-related questions and get relevant answers.
- **PDF Document Support**: Upload medical resources in PDF format to enhance the chatbot's response capabilities.
- **Memory and Query Management**: Utilizes tools like Pinecone for data storage and fast query execution.
- **AI Models**: Powered by Openai and HuggingFace models and LangChain for enhanced NLP performance.

---

## Installation

Follow these steps to run the project on your local machine.

### 1. Prerequisites
- **Python** 3.10 or higher
- **Git** (to clone the repository)
- **Anaconda** (recommended for virtual environment management)

### 2. Clone the Repository
```bash
- / git clone https://github.com/canbingol/medicine-chatbot.git
- cd medicine-chatbot
```

### 3. Create a Virtual Environment
Create and activate a virtual environment:

```bash
- conda create -n medibot python=3.10 -y
- conda activate medibot
```
### 4. Install Dependencies
```bash
- pip install -r requirements.txt
```
### 5. Add API Keys
Add the necessary API keys to the .env file:

 - "OPENAI_API_KEY": "your_openai_api_key",
 - "PINECONE_API_KEY": "your_pinecone_api_key"


### 6. Run the Project
Run the application using the following command in the main directory:

```bash
python app.py
```

Type [http://localhost:8080](http://localhost:8080) into your browser to access the interface.

Contact
For any questions or suggestions, feel free to reach out:
https://www.linkedin.com/in/canbingöl/
