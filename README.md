# AI Knowledge Worker  
### An Expert Question-Answering Agent for Insurance Tech  

This project is an AI-powered question-answering agent designed to assist employees of Insurellm, an Insurance Tech company. Built using Retrieval-Augmented Generation (RAG), the system ensures accurate and cost-effective responses by leveraging vector-based document retrieval and OpenAI's LLMs.

---

### Table of Contents  
1. Features  
2. Technologies Used  
3. Folder Structure  
4. Installation  
5. Usage  
6. Deployment  
7. Contributing  
8. License  

---

### Features  
- Retrieval-Augmented Generation using LangChain  
- Vector embedding storage using ChromaDB  
- Interactive chatbot interface powered by Gradio  
- Secure integration with OpenAI API  
- Supports text documents from the knowledge base  
- Visualizes vector embeddings using t-SNE  

---

### Technologies Used  
- Python 3.9  
- LangChain (Document loading, vector retrieval, and LLM integration)  
- OpenAI GPT-4o-mini (LLM for question answering)  
- ChromaDB (Vector database for document embeddings)  
- Gradio (Chatbot UI)  
- Matplotlib and Plotly (Vector visualization)  

---

### Folder Structure  
```plaintext  
AI_worker  
├── app.py               # Main application script  
├── knowledge-base       # Folder containing knowledge documents  
├── vector_db            # Folder for vector database storage  
├── requirements.txt     # Required dependencies  
└── README.md            # Project documentation  
Installation

To run this project locally, follow these steps:

    Clone the repository:

git clone https://github.com/yourusername/AI_knowledge_Worker.git  
cd AI_knowledge_Worker  

    Set up a virtual environment (recommended):

python -m venv venv  
source venv/bin/activate   # On Windows use: venv\Scripts\activate  

    Install dependencies:

pip install -r requirements.txt  

    Set up environment variables:
    Create a .env file in the root directory and add your OpenAI API key:

OPENAI_API_KEY=your_openai_api_key_here  

Usage

    Build the vector database (if not already created):

python app.py  

    Launch the chatbot interface using Gradio:

python app.py  

The interface will be available at:
http://localhost:7860
Deployment
Deploy on Hugging Face Spaces (Recommended)

    Upload the entire AI_worker folder to Hugging Face Spaces.
    Set the OPENAI_API_KEY under Settings > Secrets in Hugging Face.
    The app will automatically build and deploy, providing a public URL for access.

Deploy Using Docker

    Build the Docker image:

docker build -t ai-knowledge-worker .  

    Run the container:

docker run -p 7860:7860 -e OPENAI_API_KEY=your_openai_api_key_here ai-knowledge-worker  

Contributing

Contributions are welcome. Feel free to submit issues and pull requests to improve the project.

    Fork the repository
    Create a new branch:

git checkout -b feature-branch  

    Commit your changes:

git commit -m 'Add new feature'  

    Push to the branch:

git push origin feature-branch  

    Submit a pull request

License

This project is licensed under the MIT License.
Contact

For inquiries or collaboration opportunities, please reach out via LinkedIn or email.

This README is now ready to be uploaded as README.md to your GitHub repository.


---

This version is in **raw Markdown format** that you can directly copy and paste into your `README.md
