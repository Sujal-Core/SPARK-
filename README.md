```markdown
# 🚀 SPARK — Career Mentor (Carrier Catalyst)

SPARK is a comprehensive **career guidance and mentorship platform** built using **Flask (Python)**.  
It empowers users by providing **ATS-based resume analysis**, **AI-powered domain quizzes**, and **26 complete career roadmaps** with resources.  
The platform includes **user login**, **API integrations**, and an interactive **HTML/CSS/JS frontend**.

---

## 🔹 Overview

SPARK helps users identify their strengths, choose the right domain, and follow a structured roadmap through:

- **Resume Analysis (ATS score + AI insights + courses + projects + jobs)**  
- **AI-Based Domain Quiz (24 domains, 3 difficulty levels)**  
- **26 Domain Roadmaps (skills → tools → projects → certifications)**  
- **User Login System**  
- **API-Powered Resume Processing and Insights**

---

## ✨ Features

### 🧾 **1. Resume Analysis (ATS + AI Advice)**  
Users upload a resume and receive:
- ATS Score  
- Strengths & weaknesses  
- Missing keywords  
- Formatting suggestions  
- Job alignment score  
- AI-generated advice  
- Recommended courses  
- Beginner → advanced project ideas  
- Job openings based on skills & desired role  

---

### 🧠 **2. AI-Powered Domain Quiz (24 Domains)**

SPARK includes an advanced quiz system powered by AI logic.

#### ✔ 3 Difficulty Levels  
1. **Easy** – Basic MCQs  
2. **Medium** – Scenario MCQ + MSQ  
3. **Hard** – **Coding Questions**, logic-based problems, MSQ  

#### ✔ Supports 3 Question Types  
- MCQ (Single correct answer)  
- MSQ (Multiple correct answers)  
- Coding Questions (Hard level)  

#### ✔ Quiz Output  
- Best-fit domain  
- Secondary-fit domain  
- Strength score  
- Weak areas  
- Domain confidence level  

#### ✔ 24 Available Domains (Examples)  
- Data Science  
- AI/ML  
- Cybersecurity  
- Web Development  
- Cloud Computing  
- Software Engineering  
- Blockchain  
- IoT  
- DevOps  
- Digital Marketing  
- Finance Tech  
- Business Analytics  
… and many more.

---

### 🛣️ **3. Domain Roadmaps (26 Domains)**

Each roadmap includes:

#### ✔ Level-Wise Learning Path  
Beginner → Intermediate → Advanced

#### ✔ Tools & Technologies  
Languages, frameworks, cloud tools, libraries

#### ✔ Recommended Resources  
- Free & paid courses  
- Books, articles  
- YouTube playlists  
- Official documentation  

#### ✔ Projects (Portfolio Quality)  
- Beginner projects  
- Intermediate projects  
- Advanced capstone projects  

#### ✔ Certifications  
Domain-specific certifications such as:  
AWS, Azure, Google IT, CEH, Meta Frontend, IBM Data Science, etc.

#### ✔ Jobs & Salaries  
- Entry, mid, senior roles  
- Skill requirements  
- Salary expectations  

SPARK includes **26 complete roadmaps**, each with fully structured resources.

---

## 📦 Project Structure

```

Carrier_Catalyst/
│
├── Python_FIles/
│   ├── webpage.py               # Main Flask app
│   ├── ats.py                   # Resume & ATS logic
│   ├── quiz.py                  # AI-powered domain quiz logic
│   ├── roadmap.py               # 26-domain roadmap generator
│   ├── auth.py                  # User login/authentication system
│   ├── api_handler.py           # Resume analysis + job/course APIs
│   ├── feedback.py              # Resume improvement advice
│   ├── **init**.py
│   └── other Python scripts…
│
├── templates/
│   ├── index.html
│   ├── resume_result.html
│   ├── quiz.html
│   ├── roadmap.html
│   ├── login.html
│   └── more UI pages…
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── run.py
├── requirements.txt
├── README.md
└── .gitignore

````

---

## ⚡ Quick Start

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Carrier_Catalyst.git
cd Carrier_Catalyst
````

### 2️⃣ Create a virtual environment

```bash
python -m venv venv
```

Activate:

* Windows → `venv\Scripts\activate`
* macOS/Linux → `source venv/bin/activate`

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

### Method 1 — Flask CLI

Windows:

```bash
set FLASK_APP=Python_FIles.webpage
flask run
```

macOS/Linux:

```bash
export FLASK_APP=Python_FIles.webpage
flask run
```

### Method 2 — Python Direct Run

```bash
python Python_FIles/webpage.py
```

### Method 3 — Using run.py

```bash
python run.py
```

---

## 🖥 Usage

### ✔ Resume Analysis Flow

1. Upload resume (PDF/DOCX/TXT)
2. Enter target job role
3. Receive:

   * ATS Score
   * AI advice
   * Recommended courses
   * Project ideas
   * Job openings

---

### ✔ Domain Quiz Flow

1. Choose difficulty (Easy/Medium/Hard)
2. Answer MCQ, MSQ, and coding questions
3. Receive:

   * Best-fit domain
   * Domain confidence score
   * Strengths & weaknesses
   * Recommended roadmap

---

### ✔ Domain Roadmap Flow

1. Select recommended domain
2. View learning path
3. Explore tools, courses, projects
4. Download or follow step-by-step roadmap

---

## 🌐 Deployment (Render)

### Build Command

```
pip install -r requirements.txt
```

### Start Command

```
gunicorn Python_FIles.webpage:app --bind 0.0.0.0:$PORT
```

### Required Environment Variables

```
SECRET_KEY=your_secret_key
API_KEY=your_api_key_if_used
```

---

## 🔧 Dependencies

* Flask
* python-dotenv
* Gunicorn
* requests
* pdf/text extraction libraries
* Any APIs integrated

---

## 🧹 Recommended .gitignore

```
__pycache__/
*.pyc
venv/
env/
.env
instance/
*.log
.DS_Store
Thumbs.db
.vscode/
.idea/
*.cache
cache.json
secret.key
```

---

## 📄 License

Licensed under **GNU AGPLv3**
✔ Requires attribution
✔ Derivatives must remain open-source
✔ Prevents closed-source commercialization

---

## 👤 Author

**Sujal Mehra**
Developer | AI & ML Enthusiast

---

## 📌 Future Enhancements

* AI-powered resume rewriting
* Personalized learning dashboard
* Custom job alert system
* Interview preparation module

```

---

If you want:

🔥 README with **badges**  
🔥 README with **screenshots**  
🔥 README with **GIF demo**  
🔥 README in **short version**

Just tell me!
```
