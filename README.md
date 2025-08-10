# Local_News_Digest_AI
An AI-powered pipeline built with [CrewAI](https://www.crewai.com/) that **scrapes**, **summarizes**, and **classifies** the latest local news articles from any website.  
Currently configured for: [The Tribune - Uttar Pradesh](https://www.tribuneindia.com/news/state/uttar-pradesh)

---

## 📌 Features
- **Web Scraping** → Automatically fetches the latest news articles.
- **Summarization** → Condenses each article into a 2–3 sentence readable summary.
- **Categorization** → Organizes summaries into topics like:
  - Local Politics
  - Business
  - Sports
  - Technology
  - Environment
  - General News
- **Modular CrewAI Agents** → Each step handled by a specialized AI agent.

---

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/local-news-digest.git
cd local-news-digest
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Add your API Key
Create a .env file in the root directory:

env
Copy
Edit
OPENAI_API_KEY=sk-proj-xxxxxxxxxxxxxxxxxxxxxxxx
▶️ Usage
Run the script:

bash
Copy
Edit
python main.py
Output:

Prints a categorized news digest in your terminal.

Can be adapted to save results as JSON or send via email.

📂 Project Structure
bash
Copy
Edit
local-news-digest/
│-- main.py               # Main CrewAI workflow
│-- requirements.txt      # Python dependencies
│-- README.md             # Project documentation
│-- .env                  # Environment variables (not committed to git)
🔮 Future Improvements
Save results as JSON/CSV

Email or WhatsApp daily digest

Support multiple news sources

Integrate with a dashboard UI

⚠️ Disclaimer
This project is for educational purposes only. Respect website scraping rules and avoid violating any Terms of Service.
