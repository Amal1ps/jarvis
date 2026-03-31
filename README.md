# Jarvis: Agentic Security Framework 🕵️‍♂️

Jarvis is an autonomous security research assistant powered by Llama 3.3 (via Groq). It chains Kali Linux tools together based on real-time terminal output analysis to perform evidence-based security audits.

### 🚀 Features
- **Autonomous Chaining**: Jarvis decides the next tool based on the results of the previous one.
- **Loop Prevention**: Maintains a tool history to avoid redundant scans.
- **Hallucination-Free Reporting**: Final reports are strictly grounded in terminal output.
- **Auto-Saving**: Reports are saved as Markdown files in the `reports/` folder.

### 🛠️ Setup
1. **Clone the repo:**
   `git clone https://github.com/Amal1ps/jarvis.git && cd jarvis`
2. **Install requirements:**
   `pip install requests`
3. **Set your Groq API Key:**
   `export GROQ_API_KEY='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'`
4. **Run it:**
   `python jarvis.py`

### ⚠️ Disclaimer
This tool is for educational purposes and authorized security auditing only. Use responsibly.# jarvis
