# 🚀 AI-Powered Sales Data Automation & Query System

This project demonstrates an end-to-end system that **automates sales data ingestion from Gmail into a PostgreSQL database** and enables users to **query the data using natural language without writing SQL**.

It simulates a real-world business workflow where data is received periodically, processed automatically, and made available for real-time analysis.

---

## 🌐 Live Demo

Interact with the system using the public endpoint:

👉[Live Chat Interface](https://namratha9819.app.n8n.cloud/webhook/e9d8a4a7-2b08-40a0-90c1-d7ff9652122d/chat)

### 🧪 Try Sample Queries
- Top 5 customers by net sales in 2021  
- Total revenue by market  
- Sales trends over time  

The system will:
- Convert natural language → SQL  
- Execute query on PostgreSQL  
- Return real-time results  

---

## 🧠 System Architecture
Gmail → Data Extraction → PostgreSQL → AI SQL Agent → Query Results


---

## ⚙️ Key Features

- 📩 Automated data ingestion from Gmail  
- 🗄️ Real-time updates to PostgreSQL  
- 🤖 Natural Language to SQL conversion  
- 📊 Supports aggregation, filtering, and analytics  
- ⚡ Real-time query execution  

---

## 🛠️ Tech Stack

- **n8n** – Workflow Automation  
- **PostgreSQL** – Database  
- **AI Model** – Natural Language to SQL  
- **JavaScript** – Data processing  

---

## 🔄 How It Works

### 1. Email Automation Pipeline
- Detects incoming sales data via Gmail  
- Extracts and processes Excel/CSV files  
- Inserts structured data into PostgreSQL  

### 2. AI SQL Agent
- Accepts user queries in plain English  
- Uses schema context for accuracy  
- Generates SQL queries dynamically  
- Executes queries and returns results  

---

## 📦 Reusable Workflow Templates

This repository includes n8n workflow templates in JSON format.


### ⚙️ How to Use

1. Download the JSON file  
2. Open your n8n instance  
3. Click **Import Workflow**  
4. Upload the JSON file  
5. Configure:
   - Gmail credentials  
   - PostgreSQL connection  
   - AI model API key  
6. Run the workflow  

---


## 📊 Sample Queries

| Query | Description |
|------|------------|
| Top 5 customers by net sales | Customer ranking |
| Total revenue by region | Aggregated insights |
| Sales trends by year | Time-based analysis |

---

## 🎥 Social Profiles

👉 [YouTube](https://youtu.be/VrZaqymhyOs)
💼 [LinkedIn](https://www.linkedin.com/posts/namratha-ravula_sql-dataanalytics-ai-ugcPost-7446581868902334465-t6A4?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD-2POMBXhq2oXj94XjyWKK8nb5c4ZnTz6w)
---

## 🎯 Use Case

This system is useful in scenarios where:
- Data arrives periodically (daily/monthly)  
- Manual data entry needs to be eliminated  
- Non-technical users require quick insights  
- Real-time analytics is needed  

---

## ⚠️ Important Notes

- Ensure database schema matches expected structure  
- Update credentials before running workflows  
- Sample data is included for testing  

---

## 💡 Final Thoughts

This project combines **automation + AI-powered querying** to create a seamless data pipeline that enables faster and more efficient decision-making.

## 🔗 Connect With Me
**Ravula Namratha**
ravulanamratha98@gmail.com

