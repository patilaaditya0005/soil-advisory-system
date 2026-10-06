# 🌱 Soil Advisory System — Team CodeHarvest

**AI-powered soil health analysis and advisory system with an intelligent chatbot for farmers.**

Developed as part of **TechForGood 2026** — IEEE Student Branch, MIT ADT University.

## 📌 Overview

The Soil Advisory System helps farmers understand soil health and make informed agricultural decisions using soil parameters and AI-powered guidance.

The system analyzes soil pH and NPK nutrient values to identify potential deficiencies, suggest suitable crops, and provide fertilizer recommendations. It also includes KisanBot, a multilingual chatbot designed to assist farmers.

## ✨ Features

- **Soil Health Analysis:** Evaluate soil conditions using pH and NPK values.
- **Nutrient Deficiency Detection:** Identify potential nutrient deficiencies.
- **Crop Suitability:** Recommend crops based on soil conditions.
- **Fertilizer Recommendations:** Provide fertilizer guidance and dosage recommendations.
- **KisanBot Chatbot:** AI-powered assistance for farmers.
- **Multilingual Support:** English, Hindi, Marathi, and Gujarati.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | React, Vite |
| Backend | Python, FastAPI |
| AI Integration | Google Gemini API |
| Frontend Deployment | Vercel |
| Backend Deployment | Render |

## 🚀 Getting Started

### Prerequisites

- Python installed
- Node.js and npm installed
- Git installed
- Google Gemini API key for AI chatbot functionality, if required

### 1. Clone the Repository

```bash
git clone https://github.com/patilaaditya0005/soil-advisory-system.git
cd soil-advisory-system
```

### 2. Configure the Backend

Open a terminal in the project root:

```bash
cd backend
python -m venv .venv
```

Activate the virtual environment on Windows:

```bat
.venv\Scripts\activate
```

Install the Python dependencies:

```bash
python -m pip install -r requirements.txt
```

Configure the required environment variables using a local `.env` file, following the variable names expected by the backend code. Never commit API keys or other secrets.

Start the API using the entry point configured in the project:

```bash
uvicorn main:app --reload
```

This command assumes `main.py` defines a FastAPI instance named `app`.

### 3. Configure the Frontend

Open a second terminal in the project root:

```bash
cd frontend
npm ci
npm run dev
```

Open the local URL printed by Vite in your terminal.

### 4. Build the Frontend

To check whether the frontend builds successfully:

```bash
npm run build
```

### Troubleshooting

- Ensure Python and Node.js are installed and available on your PATH.
- Verify the backend's required environment variables before starting the application.
- Check the frontend API URL configuration if the frontend cannot reach the backend.
- Use the project's actual backend entry point if it differs from `main:app`.


## 🔐 Environment Variables

Store API keys and other secrets in local environment files. Never commit real credentials to GitHub.

If the project uses environment files, add the relevant secret-bearing files to `.gitignore` and provide a sanitized example configuration where appropriate.

## 👥 Team and Acknowledgements

**Team:** CodeHarvest  
**Project:** TechForGood 2026  
**Institution:** IEEE Student Branch, MIT ADT University

This repository is a fork of the original project by [AbbasML](https://github.com/AbbasML/soil-advisory-system). Original project and team contributions should be credited appropriately.

## 📄 License

Refer to the original repository's license and applicable project permissions before redistributing or reusing the code.
