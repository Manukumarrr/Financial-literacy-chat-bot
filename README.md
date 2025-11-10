# 💰 FinBot - AI-Powered Financial Literacy Assistant for Low-Income Communities 🤖

## 🌍 Overview

**FinBot** is an innovative **AI-powered financial literacy assistant** designed to empower **low-income and multilingual communities** by providing real-time financial education, scam alerts, and budgeting guidance through **WhatsApp**.  
Built using **FastAPI**, **Hugging Face NLP models**, and the **WhatsApp Cloud API**, FinBot simplifies financial learning by interacting in users’ native languages — making financial knowledge **accessible, secure, and inclusive**.

---

## 🔑 Key Features

### 💬 Multilingual Financial Education
FinBot provides easy-to-understand financial guidance in multiple languages such as English, Hindi, and more using **Google Translate API** and **Hugging Face** models.

### 🧠 AI-Powered Learning
Leverages Natural Language Processing (NLP) to explain financial terms, concepts, and tips conversationally.

### 🔔 Real-Time Scam Alerts
Automatically warns users about trending **financial scams** and **fraudulent schemes**, enhancing financial safety in vulnerable communities.

### 📊 Budgeting & Saving Tips
Provides actionable advice on budgeting, saving, and investment basics to promote better money management habits.

### 💬 WhatsApp Integration
Uses **WhatsApp Cloud API** to deliver messages directly to users’ phones — enabling easy, real-time interaction without requiring additional apps.

### 🛡️ Secure & Scalable
Employs **MongoDB Atlas** for safe data handling and ensures scalability across communities with minimal infrastructure.

---

## 🧩 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **FastAPI** | Backend framework for building asynchronous APIs. |
| **Hugging Face Transformers** | Provides NLP models for text understanding and response generation. |
| **Google Translate API** | Enables dynamic multilingual communication. |
| **MongoDB Atlas** | Cloud-based NoSQL database for storing user interactions securely. |
| **WhatsApp Cloud API** | Real-time messaging platform integration. |
| **Python-dotenv** | Handles environment variables and API key management. |
| **Requests / Aiohttp** | For HTTP communication and API calls. |

---

## ⚙️ How It Works

### 1. **Message Reception**
A user sends a message to the FinBot WhatsApp number.

### 2. **Language Detection & Translation**
FinBot detects the message language and translates it (if needed) to English using **Google Translate API**.

### 3. **AI Processing**
The message is passed to an NLP model (via **Hugging Face**) that determines the financial intent and generates a suitable response.

### 4. **Response Translation**
The response is translated back to the user’s preferred language.

### 5. **WhatsApp Reply**
FinBot replies to the user instantly on WhatsApp using the **WhatsApp Cloud API**.

---

## 🧰 Installation

To get started with **FinBot - AI-Powered Financial Literacy Assistant**, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/FinBot.git
cd FinBot
