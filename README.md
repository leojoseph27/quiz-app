# 🧠 MCQ Generator using AI - Auto Create Questions from Text Files

A ⚡ Flask web application that **automatically generates multiple-choice questions (MCQs)** from text files using **Google Generative AI**. The app supports multiple file formats and offers an **interactive quiz experience** with timers, bookmarks, scoring, and explanations.

🔗 **[Live Demo →](https://aiquizer.onrender.com/)**

---

## 🚀 Features

### 🎯 Core Features
- **🤖 AI-Powered Question Generation**
  - Automatic MCQ creation from text input
  - Supports difficulty levels: Easy, Intermediate, Hard
  - Context-aware question generation
  - Smart content structuring

- **📂 File Processing**
  - Support for PDF, DOCX, and TXT files
  - Secure and validated file uploads
  - Accurate text extraction
  - Robust error handling

- **📝 Interactive Quiz System**
  - Real-time timer ⏱️
  - Bookmark questions 🔖
  - Skip options ⏭️
  - Quiz progress tracking 📊
  - Performance insights & analytics

- **📑 Result Management**
  - Detailed PDF result reports 🧾
  - Score breakdown and feedback
  - Auto-generated study notes 🧠
  - Answer explanation for learning

---

### 💻 User Interface
- Responsive design across devices 📱💻🖥️
- 🌙 Dark / ☀️ Light mode support
- Smooth navigation and layout
- 🔔 Real-time notifications
- Visual progress indicators 📈

---

## 🧱 Project Structure

```
MCQ-Generator/
├── app.py                 # 🚀 Main Flask application
├── static/
│   ├── style.css         # 🎨 CSS styles
│   └── uploads/          # ⬆️ File upload directory
├── templates/
│   ├── index.html        # 🏠 Home page
│   ├── quiz.html         # ❓ Quiz interface
│   ├── scoreboard.html   # 🏆 Scoreboard
│   └── results.html      # 📄 Detailed results
├── uploads/              # 🗃️ Temporary file storage
├── results/              # 📁 Generated result PDFs
├── .env                  # 🔐 Environment variables
└── requirements.txt      # 📦 Python dependencies
```

---

## ⚙️ Installation & Setup

1. **📥 Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/MCQ-Generator.git
   cd MCQ-Generator
   ```

2. **🐍 Create Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **📦 Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **🔧 Environment Setup**
   Create a `.env` file and add the following:
   ```
   GOOGLE_API_KEY=your_google_ai_api_key
   FLASK_SECRET_KEY=your_secret_key
   ```

5. **▶️ Run the Application**
   ```bash
   python app.py
   ```

---

## 🛠️ Technologies Used

### 🔙 Backend (Python)
- Flask 🐍 – Web Framework  
- Google Generative AI 🤖 – Question Generation  
- pdfplumber 📄 – PDF Text Extraction  
- python-docx 📃 – DOCX File Handling  
- FPDF 📑 – PDF Report Creation  
- Werkzeug 🛠️ – File Management

### 🎨 Frontend
- HTML5 📘 – Page Structure  
- CSS3 🎨 – Styling & Themes  
- JavaScript ⚡ – Interactivity  
- Font Awesome 🎯 – Icons

### 🧰 Development Tools
- Git 🔁 – Version Control  
- VS Code / PyCharm 💻 – Code Editors  
- Python 3.x 🐍 – Programming Language

---







