# RevwAI 🤖

**Smarter Code Reviews. Powered by AI.**

RevwAI is an intelligent PR reviewer that analyzes code changes, leaves insightful feedback, and helps teams maintain high-quality codebases — automatically.

---

## 🚀 Features

- 🔍 AI-generated review comments for PRs
- 🧠 Code analysis using language models
- ✅ Integrates with GitHub Actions
- 📊 Configurable review rules (style, logic, performance, etc.)

---

## 🛠️ Installation
1. Install claude desktop client(This is not yet supprorted for Linux users)
2. Install the required dependencies:
3. Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/revwai.git
cd revwai
```
4. Install the required dependencies:
```bash
pip install -r requirements.txt
```
5. Set up your GitHub personal access token.
   - Go to your GitHub account settings.
   - Navigate to Developer settings > Personal access tokens.
   - Generate a new token with the `repo` scope.
   - Copy the token and store it securely.
6. Create a `.env` file in the project root directory and add your GitHub token.
7. Run the application:
```bash
python pr_analyzer.py
```