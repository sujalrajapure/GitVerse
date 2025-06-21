

# 📊 GitHub Repository Analyzer with AI Summary

**GitHub Repository Analyzer** is a simple Python tool that fetches key data from any GitHub repository and generates an AI-powered summary using the Gemini API. It helps developers quickly understand a repository’s popularity, activity, and maintenance status without manually checking stats.

---

## ⚙️ Features

* ✅ Fetches real-time repository data: stars, forks, issues, pull requests, contributors.
* ✅ Generates an AI-written summary explaining the repository’s health and activity.
* ✅ Clean, readable console output and optional report file.
* ✅ Easy to configure and extend.

---

## 🛠️ Tech Stack

* Python
* GitHub REST API
* Gemini API (for AI summaries)
* Requests library

---

## 🚀 How to Use

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/github-repo-analyzer.git
cd github-repo-analyzer
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Add Your API Keys

* **GitHub API Token:** To handle rate limits.
* **Gemini API Key:** To generate summaries.

Create a `.env` file:

```env
GITHUB_TOKEN=your_github_token
GEMINI_API_KEY=your_gemini_api_key
```

### 4️⃣ Run the Analyzer

```bash
python analyzer.py --repo owner/repo-name
```

Example:

```bash
python analyzer.py --repo tensorflow/tensorflow
```

---

## 📂 Project Structure

```
github-repo-analyzer/
│
├── analyzer.py        # Main script
├── requirements.txt   # Python dependencies
├── .env               # Your API keys (not committed)
└── README.md          # Project documentation
```

---

## ✅ Example Output

```
Repository: tensorflow/tensorflow
Stars: 185k
Forks: 85k
Open Issues: 1,200
Pull Requests: 300

AI Summary:
"This repository is highly active and widely used in production and research. Frequent updates and a large community make it a reliable choice for deep learning tasks."
```

---

## 📌 Future Improvements

* Export reports to PDF or Markdown.
* Support batch analysis for multiple repositories.
* Add a simple web interface.

---

## 🤝 Contributing

Feel free to open issues or pull requests to add new features or fix bugs!

---

## 📜 License

This project is for educational purposes only.

---

If you want, I can also prepare:
✅ `requirements.txt` content
✅ Example `.env` file
✅ Example `analyzer.py` template

Just say **“Yes, give me the code files too!”** 🚀✨
