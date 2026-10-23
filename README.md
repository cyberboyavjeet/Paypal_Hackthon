# Paypal_Hackthon
An AI-powered B2B financial risk management system that predicts invoice defaults using TensorFlow and automates collections via the PayPal API.
# FlowSync 💸🤖

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)

**An AI-powered financial risk management system that predicts B2B invoice defaults and automates collections via the PayPal API.**

## 📌 The Problem
Small and Medium Enterprises (SMEs) frequently face critical cash-flow crises due to unpredictable, late B2B payments. Traditional financial software relies on passive ledgers—telling a business they are out of money *after* it happens. Business owners lack the tools to foresee payment risks and struggle to take immediate, actionable steps to secure their receivables.

## 💡 The Solution
**FlowSync** replaces passive tracking with an active, intelligent agent. By leveraging a TensorFlow Artificial Neural Network trained on historical payment data, the system evaluates outstanding invoices to generate real-time risk scores (0-100). When an account is flagged as high-risk, FlowSync dynamically generates a secure PayPal checkout link, allowing businesses to proactively secure their cash flow before a default occurs. 

---

## ✨ Key Features
*   **🧠 Predictive Risk Scoring:** Uses a custom Artificial Neural Network to calculate the exact probability of an invoice defaulting based on temporal data, amounts, and historical client behavior.
*   **⚡ Automated PayPal Remediation:** One-click integration with the PayPal REST API (v2/checkout/orders) instantly generates shareable payment links for at-risk accounts.
*   **📊 Dynamic Cash-Flow Forecasting:** A reactive dashboard utilizing Recharts to project 90-day cash survival lines based on live invoice statuses.
*   **🗄️ Live Full-Stack Architecture:** Fully decoupled system featuring a lightning-fast FastAPI backend, persistent SQLite database, and a modern React/Tailwind frontend.

---

## 🛠️ Tech Stack

### Frontend
*   **Framework:** React.js (Vite) + TypeScript
*   **Styling:** Tailwind CSS
*   **Data Visualization:** Recharts
*   **State Management:** React Hooks

### Backend
*   **Framework:** FastAPI (Python)
*   **Database:** SQLite via SQLAlchemy (ORM)
*   **Server:** Uvicorn

### Artificial Intelligence & Machine Learning
*   **Framework:** TensorFlow / Keras
*   **Data Processing:** Scikit-learn, Pandas, NumPy
*   **Features:** Mathematical class weighting, Label Encoding, MinMax Scaling

### External Integrations
*   **Payments:** PayPal Developer REST API 

---

## 🚀 Local Installation & Setup

### Prerequisites
*   Node.js (v16+)
*   Python (3.9+)
*   A PayPal Developer Account (for Sandbox API credentials)

### 1. Clone the Repository
```bash
git clone [https://github.com/cyberboyavjeet/Paypal_Hackthon.git](https://github.com/yourusername/FlowSync.git)
cd FlowSync
