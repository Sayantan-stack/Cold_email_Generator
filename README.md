# Cold Email Generator for Services Company

This tool is built using **GROQ**, **LangChain**, and **Streamlit**, and is designed to help service-based companies send **personalized cold emails** based on company job listings.

## 🔍 What It Does

Users provide the **URL of a company's careers page**, and the tool:

1. Extracts job listings from the page.
2. Matches job descriptions with relevant portfolio links from a vector database.
3. Generates **customized cold emails** for outreach.

---

## 💡 Use Case

Imagine this scenario:

- **Nike** is hiring a *Principal Software Engineer* and is investing time and resources in hiring, onboarding, and training.
- **Atliq**, a software development company, can provide dedicated engineers for such roles.
- **Mohan**, a business development executive from Atliq, wants to reach out to Nike with a relevant offer.

This tool helps Mohan craft **precise and persuasive cold emails**, tailored to the job listing on Nike’s careers page.

---

## ⚙️ Setup Instructions

### 1. API Key
- Get your `GROQ_API_KEY` from:
  👉 https://console.groq.com/keys

- Update the `.env` file located inside the `app/` directory with your API key: GROQ_API_KEY=your_api_key_here


### 2. Install Dependencies

Run the following command:

```bash
pip install -r requirements.txt


### 3. Launch the App

```bash
streamlit run app/main.py

🧠 Built With
GROQ

LangChain

Streamlit


