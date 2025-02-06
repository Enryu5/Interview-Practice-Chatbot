## **HireHelp – AI-Powered Interview Practice Chatbot**  

**HireHelp** is an AI-driven chatbot designed to assist users in **practicing job interviews** with realistic, dynamic interactions. The chatbot offers two distinct interview modes:  

- **General Interview Mode** – Simulates traditional job interviews, covering behavioral and role-specific questions.  
- **Live Coding Interview Mode** – Facilitates coding assessments with real-time programming challenges.  

## **Features**  

✅ **Two Interview Modes**: Choose between **General** and **Live Coding** interview types.  
✅ **AI-Powered Questions & Feedback**: Uses **two LLMs** via [Together.ai](https://api.together.ai/) API for interactive Q&A.  
✅ **PDF Resume Analysis**: Upload a resume to customize interview questions based on user experience.  
✅ **Multilingual Support**: Available in multiple languages, including English, Bahasa Indonesia, French, Spanish, and more.  
✅ **Word Limit & Token Budget Management**: Controls user response length to maintain concise answers.  
✅ **EC2 Instance Detection**: Identifies AWS instance details for cloud-based deployments.  
✅ **Conversation History & Export Options**: Save, search, and export past interview sessions in **TXT, CSV, or JSON**.  
✅ **Streamlit Interface**: Lightweight web-based UI for a smooth user experience.  

## **Installation**  

1. **Clone the repository**:  
   ```sh
   git clone https://github.com/your-repo/hirehelp.git  
   cd hirehelp  
   ```  
2. **Create a virtual environment** (optional but recommended):  
   ```sh
   python -m venv venv  
   source venv/bin/activate  # For macOS/Linux  
   venv\Scripts\activate  # For Windows  
   ```  
3. **Install dependencies**:  
   ```sh
   pip install openai tiktoken requests streamlit PyMuPDF python-dotenv  
   ```  
4. **Set up environment variables** in a `.env` file:  
   ```env
   OPENAI_API_KEY=your_api_key  
   ```  
5. **Run the application**:  
   ```sh
   streamlit run main.py  
   ```  

## **Usage**  

1. Select **interview mode** from the sidebar.  
2. Upload your **resume (PDF format)** for personalized interview questions.  
3. Choose your **job position and qualifications** to tailor responses.  
4. Start the interview and **chat with the AI**.  
5. **Export your conversation** for later review.  
