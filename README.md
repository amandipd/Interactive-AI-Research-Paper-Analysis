# Interactive AI Research-Paper Analysis Chatbot
## Project Link (may take a minute to load): [Website](https://interactive-ai-research-paper-analysis.onrender.com)
### Preview:
![image](https://github.com/user-attachments/assets/e5a5c25f-c73b-4323-b5f6-dcb53a2351ce)

## Brief Description
This research paper analyzer is a full-stack LLM web application built in Flask that allows users to interact with uploaded research papers (PDFs) through an AI-powered chatbot. It processes uploaded PDFs by converting them into searchable vector embeddings through FAISS (Facebook AI Similarity Search) indexes and uses the Mistral AI API to generate context-based answers. Some examples of questions one may ask to the chatbot can include:

*What data collection techniques were applied in this study? <br />
What are the parameters or variables studied? <br />
What conclusions were drawn from the hypothesis? <br />
What gaps in literature does this paper address?*

## Setup: Run Locally
Follow these steps to set up and run the project locally:

### 1. Clone the Repository:
```bash
git clone https://github.com/yourusername/interactive-ai-research-paper-analysis.git
cd interactive-ai-research-paper-analysis
```

### 2. Create a virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### 3. Install Dependencies
Install all required dependencies using the requirements.txt file:
```bash
pip install -r requirements.txt
```

### 4. Set up Environment Variables
Create a .env file in the project root directory and add your [Mistral API key](https://auth.mistral.ai/ui/login?flow=f6413b16-9fe4-4bc0-8d1f-e59460fb8f86):
```bash
MISTRAL_API_KEY=your_api_key_here
```
###

### 5. Run the Application
Start the Flask application:
```bash
python app.py
```
### 5. Access the Application
Open your browser and navigate to http://127.0.0.1:5000/

## Tech Stack & Frameworks
Python, LangChain, Mistral AI API, Flask, FAISS

