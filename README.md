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

To run the project locally, first clone the repository:

```bash
git clone https://github.com/patilaaditya0005/soil-advisory-system.git
cd soil-advisory-system
```

### Prerequisites

- Python installed
- Node.js and npm installed
- Google Gemini API key, if required by the chatbot or backend

### Backend Setup

Follow the backend instructions and dependency files in the `backend` directory. Configure required environment variables locally and start the FastAPI application using the project's documented entry point.

### Frontend Setup

Follow the frontend instructions and dependency files in the `frontend` directory. Install dependencies and start the Vite development server using the scripts defined in `package.json`.

**Note:** Confirm the actual entry points, dependency files, environment variable names, and startup commands in the repository before running the application.

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
