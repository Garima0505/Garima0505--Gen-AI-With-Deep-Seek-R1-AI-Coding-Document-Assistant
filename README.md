🚀 Gen-AI-With-Deep-Seek-R1: AI Coding & Document Assistant
🔗 GitHub Repo: [Your Repo Link]

📌 Overview
Gen-AI-With-Deep-Seek-R1 is a powerful AI-driven coding and research assistant that helps with: ✅ AI-powered coding help with debugging and documentation
✅ Document Q&A using RAG-based PDF retrieval
✅ Seamless UI with Dark Mode and Chat History

🛠️ Features
1️⃣ DeepSeek Code Companion (AI Coding Assistant)
🤖 AI-powered coding help (Python, Debugging, Documentation)
🔥 Powered by DeepSeek-R1 models (1.5B & 3B)
💡 Solution design with strategic print statements
🎨 Custom UI with chat history
2️⃣ DocuMind AI (Document Q&A)
📄 PDF Upload & Analysis
🔎 Retrieves relevant content using embeddings
🤖 AI-generated answers based on document context
🎨 Stylized chat interface for easy reading


# Clone the repo
git clone https://github.com/your_username/Gen-AI-With-Deep-Seek-R1.git
cd Gen-AI-With-Deep-Seek-R1

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate      # On Windows

# Install dependencies
pip install -r requirements.txt


🚀 Usage
Run DeepSeek Code Companion
sh
Copy
Edit
streamlit run app.py
📌 Access at: http://localhost:8501

Run DocuMind AI
sh
Copy
Edit
streamlit run rag_deep.py
📌 Access at: http://localhost:8502


📌 Tech Stack
🏗 LangChain
🤖 Ollama (DeepSeek-R1 LLM)
🎨 Streamlit
📄 pdfplumber (for PDF processing)