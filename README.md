GENAI-Agent

An AI-powered research assistant built with LangChain, Streamlit, and Groq LLMs.
This project lets you query Arxiv, Wikipedia, and DuckDuckGo in natural language, and the agent will fetch, process, and summarize results for you.

🚀 Features

🔍 Search across Arxiv (research papers), Wikipedia, and the web.

🧠 Uses LangChain Agents to reason about tool usage.

⚡ Runs on Groq LLMs for ultra-fast responses.

📊 Streamlit front-end with live output & callbacks.

🌐 Ready for deployment on Streamlit Cloud or locally.

🛠️ Installation
1. Clone the repo
git clone https://github.com/amankamlesh/GENAI-agent.git
cd GENAI-agent

2. Create a virtual environment
python3.13 -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows

3. Install dependencies
pip install --upgrade pip
pip install -r requirements.txt

⚙️ Environment Variables

Create a .env file in the project root with your API keys:

GROQ_API_KEY=your_groq_api_key_here

▶️ Usage

Run the Streamlit app locally:

streamlit run app.py


The app will start on http://localhost:8501
.

📦 Requirements

All dependencies are listed in requirements.txt
.
Key packages:

streamlit

langchain

langchain-community

langchain-groq

arxiv

wikipedia

duckduckgo-search

transformers

sentence-transformers

🌐 Deployment (Streamlit Cloud)

Push your code to GitHub.

Connect your repo to Streamlit Cloud.

Add your environment variables in Streamlit Cloud → Settings → Secrets.

Deploy 🚀
