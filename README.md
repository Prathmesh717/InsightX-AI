# 🚀 InsightX AI

### AI-Powered Conversational Business Intelligence Platform

**InsightX AI** is a full-stack, AI-powered Business Intelligence platform that enables users to explore large-scale transaction data through **natural-language conversations, interactive dashboards, statistical analytics, fraud analysis, and AI-generated business insights**.

Instead of manually writing SQL queries or analyzing spreadsheets, users can simply ask questions about their data and receive meaningful, data-driven answers.

> **Ask your data. Understand your business. Make better decisions.**

---

## 🌟 Why InsightX AI?

Traditional Business Intelligence platforms often require users to understand:

* SQL
* Data visualization tools
* Complex dashboards
* Statistical analysis
* Data preparation

InsightX AI simplifies this workflow by combining **Generative AI with automated data analytics**.

```text
             Natural Language Question
                       │
                       ▼
              ┌─────────────────┐
              │    InsightX AI  │
              └────────┬────────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
       Data Analytics        Generative AI
             │                   │
             └─────────┬─────────┘
                       ▼
                Business Insight
                       │
             ┌─────────┼─────────┐
             ▼         ▼         ▼
          Answer    Metrics   Recommendation
```

---

# ✨ Key Features

## 🤖 Conversational Data Analysis

Users can ask questions about their dataset using natural language.

### Example Questions

```text
Which state has the highest transaction volume?
```

```text
What is the overall fraud rate?
```

```text
Which payment network has the highest fraud rate?
```

```text
What time of day has the highest transaction activity?
```

```text
Which bank processes the most transactions?
```

```text
What are the major patterns in the transaction data?
```

The system converts the user's question into an analytical request and generates a business-oriented response.

---

# 📊 Interactive Business Intelligence Dashboard

InsightX AI automatically calculates and visualizes important business KPIs.

### Key Metrics

* Total Transactions
* Total Transaction Value
* Average Transaction Amount
* Median Transaction Amount
* Transaction Success Rate
* Fraud Cases
* Fraud Rate
* Transaction Volume
* Peak Transaction Hour

### Analytics Dimensions

* State
* Bank
* Payment Network
* Transaction Category
* Transaction Type
* Device
* Age Group
* Time of Day
* Date

---

# 🔍 Fraud Analytics

InsightX AI provides dedicated analysis of transaction fraud patterns.

Users can investigate fraud across:

* States
* Banks
* Payment networks
* Devices
* Transaction categories
* Transaction types
* Age groups
* Time periods

This helps identify potentially high-risk segments and supports data-driven fraud monitoring.

---

# 📈 Interactive Data Visualization

The platform uses interactive charts to make complex datasets easier to understand.

Visualizations include:

* 📊 Bar Charts
* 📈 Line Charts
* 🥧 Pie Charts
* 📉 Area Charts
* 🎯 Radar Charts
* 🔢 KPI Cards
* 🖱️ Interactive Tooltips

---

# 📁 CSV Data Upload

Users can upload their own transaction datasets through the application.

The backend automatically processes the uploaded CSV and generates:

```text
Dataset Profile
      │
      ├── Row Count
      ├── Column Count
      ├── Numerical Statistics
      ├── Categorical Statistics
      ├── Missing Values
      └── Business Metrics
```

This makes the platform adaptable beyond the default dataset.

# 🏗️ Architecture

```text
┌───────────────────────────────────────────────┐
│                   USER                        │
│                                               │
│   Ask Questions • Upload Data • Explore BI   │
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│              REACT FRONTEND                   │
│                                               │
│ Dashboard │ AI Chat │ Charts │ CSV Upload    │
└───────────────────────┬───────────────────────┘
                        │
                     REST API
                        │
                        ▼
┌───────────────────────────────────────────────┐
│              FASTAPI BACKEND                  │
│                                               │
│ Data Processing │ Analytics │ AI Integration │
└───────────────┬───────────────────┬───────────┘
                │                   │
                ▼                   ▼
       ┌─────────────────┐   ┌─────────────────┐
       │ Pandas / NumPy  │   │   AI Providers  │
       │                 │   │                 │
       │ Data Analytics  │   │ NVIDIA NIM      │
       │ Statistics      │   │ Anthropic       │
       └─────────────────┘   └─────────────────┘
```

---

# 🛠️ Technology Stack

## Frontend

* React.js
* JavaScript
* JSX
* Recharts
* HTML5
* CSS3

## Backend

* Python
* FastAPI
* Uvicorn
* Pandas
* NumPy
* python-dotenv
* OpenAI-compatible SDK

## Artificial Intelligence

* Generative AI
* NVIDIA NIM
* Llama
* NVIDIA Nemotron
* Anthropic Claude

## Data Analytics

* Pandas
* NumPy
* Statistical Analysis
* Exploratory Data Analysis
* Business Intelligence

## Data

* CSV
* UPI Transaction Dataset
* 250,000+ Transactions

---

# 📂 Project Structure

```text
InsightX-AI/
│
├── Backend/
│   ├── Main.py
│   ├── Insightxmodel.py
│   ├── upi_transactions_2024.csv
│   ├── requirements.txt
│   └── .env
│
├── Sample Query/
│   └── Sample Question.md
│
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── InsightX_AI.jsx
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   ├── index.css
│   ├── App.test.js
│   ├── setupTests.js
│   └── reportWebVitals.js
│
├── package.json
├── package-lock.json
└── README.md
```

---

# 📊 Dataset

The default application uses a **250,000-row UPI transaction dataset from India**.

### Dataset Metrics

| Metric                |        Value |
| --------------------- | -----------: |
| Transactions          |      250,000 |
| Transaction Volume    | ₹32.79 Crore |
| Average Transaction   |    ₹1,311.76 |
| Median Transaction    |         ₹629 |
| Success Rate          |       95.05% |
| Fraud Cases           |          480 |
| Fraud Rate            |       0.192% |
| Peak Transaction Hour |         7 PM |

---

# 🔄 How It Works

## 1. Upload Data

The user uploads a CSV transaction dataset.

↓

## 2. Data Processing

The FastAPI backend loads and processes the dataset using Pandas.

↓

## 3. Analytics Generation

The system calculates:

* KPIs
* Aggregations
* Statistical summaries
* Fraud metrics
* Category distributions
* Time-based trends

↓

## 4. User Asks a Question

The user interacts with the conversational AI interface.

↓

## 5. AI Analysis

The relevant analytical context is provided to the selected AI model.

↓

## 6. Business Insight

The system generates a structured response containing:

```text
Direct Answer
      ↓
Key Numbers
      ↓
Important Pattern
      ↓
Business Recommendation
```

---

# 🧪 Example

### User Question

```text
Which state has the highest transaction volume?
```

### InsightX AI

The system analyzes the transaction dataset and returns the relevant state, transaction count, transaction value, and supporting business context.

This allows users to move from:

```text
Raw Data
   ↓
Analysis
   ↓
Insight
   ↓
Decision
```

without manually querying the dataset.

---

# ⚙️ Installation

## Prerequisites

Make sure you have:

* Python 3.10+
* Node.js 18+
* npm
* Git

---

## 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/InsightX-AI.git

cd InsightX-AI
```

---

# 🐍 Backend Setup

Navigate to the backend:

```bash
cd Backend
```

Create a virtual environment:

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🔐 Environment Configuration

Create a `.env` file inside `Backend`.


Add the following to `.gitignore`:

```text
.env
venv/
__pycache__/
node_modules/
```

---

# ▶️ Start the Backend

From the `Backend` directory:

```bash
uvicorn Main:app --reload --port 8000
```

Backend:

```text
http://localhost:8000
```

FastAPI Swagger documentation:

```text
http://localhost:8000/docs
```

---

# ⚛️ Frontend Setup

Open another terminal and return to the project root:

```bash
cd ..
```

Install dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

The application will normally be available at:

```text
http://localhost:3000
```

---

# 🔌 API

The backend exposes REST APIs for:

### Health Check

```text
GET /api/health
```

### Dashboard Analytics

```text
GET /api/dashboard
```

### Dataset Overview

```text
GET /api/overview
```

### AI Chat

```text
POST /api/chat
```

### CSV Upload

```text
POST /api/upload-csv
```

### Session Management

```text
GET /api/session/{id}
DELETE /api/session/{id}
```

For the complete API specification:

```text
http://localhost:8000/docs
```

---

# 💼 Business Applications

InsightX AI can be adapted for:

* 🏦 Banking Analytics
* 💳 Payment Analytics
* 🔍 Fraud Detection
* 📊 Business Intelligence
* 👥 Customer Analytics
* 📈 Financial Analytics
* 🏢 Enterprise Reporting
* 💰 FinTech Applications
* 🎯 Decision Support Systems

# 🎯 Project Highlights

**InsightX AI demonstrates practical integration of:**

* Generative AI
* Business Intelligence
* Data Analytics
* Full-Stack Development
* Natural Language Interfaces
* Fraud Analytics
* Interactive Data Visualization
* REST APIs
* Large-scale CSV processing
