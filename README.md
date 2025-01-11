
# 🌐 QuickURL: URL Research and Q&A  

**Quickly analyze and understand web content using AI-driven summarization and interactive Q&A.**  

---

## 🚀 About QuickURL  
QuickURL is a Streamlit-powered app that helps users simplify online research by summarizing the content of URLs and providing intelligent answers to questions based on that content. Utilizing **Google's Gemini 1.5 Flash Model**, QuickURL makes web exploration faster, smarter, and more efficient.

With QuickURL, you can:  
- **Summarize web pages**: Extract the essence of online content without reading everything.  
- **Ask questions**: Query the extracted information for direct answers.  
- **Save time and effort**: Let AI handle content analysis while you focus on insights.

---

## ✨ Features  
- **Summarization**: Paste a URL, and get a concise, AI-generated summary of its content.  
- **Interactive Q&A**: Ask specific questions about the content and receive direct answers.  
- **History Tracking**: Session-based tracking of processed URLs, summaries, and Q&A for reference.  
- **AI-Powered Insights**: Leverage Google's advanced **Gemini 1.5 Flash Model** for natural language understanding.  
- **Streamlit Interface**: Intuitive design for easy interactions.

---

## 🛠️ Installation  

### Prerequisites  
- Python 3.8 or higher.  
- A valid **Google API Key** for accessing the Gemini model.

### Steps  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/your-username/QuickURL.git
   cd QuickURL
   ```  

2. **Create and Activate a Virtual Environment**:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```  

3. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```  

4. **Set Up Environment Variables**:  
   Create a `.env` file in the root directory with the following content:  
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key
   ```  

5. **Run the Application**:  
   ```bash
   streamlit run main.py
   ```  

---

## 📖 How It Works  
1. **Input URLs**: Use the sidebar to provide up to three URLs.  
2. **Process URLs**: Click the "Process URLs" button to generate AI summaries of the content.  
3. **Interactive Q&A**: Ask questions in the provided text input fields to receive targeted answers.  
4. **Review History**: Access session-based summaries and Q&A for processed URLs.

---

## 🛠️ Technologies Used  
- **Streamlit**: For an interactive and user-friendly interface.  
- **Google Gemini AI**: Provides AI-powered summarization and Q&A.  
- **python-dotenv**: For managing environment variables.  

---

## 🌟 Why QuickURL?  
QuickURL is perfect for students, professionals, and researchers who need quick insights into web content. Say goodbye to information overload and hello to a faster, AI-enhanced way of understanding online information.

---

## 🤝 Contribution  
Contributions are welcome! If you'd like to improve QuickURL or suggest new features:  
1. Fork this repository.  
2. Create a feature branch: `git checkout -b feature/your-feature-name`.  
3. Commit your changes: `git commit -m 'Add your feature'`.  
4. Push to the branch: `git push origin feature/your-feature-name`.  
5. Open a Pull Request.

---

## 📝 License  
This project is licensed under the **MIT License**.  

--- 
