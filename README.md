# n8n-data-analytics-assistant

A small AI-powered data analytics assistant built using **n8n**, **Google Gemini**, and **Google Sheets**.

The goal of this project is to explore how AI and workflow automation can be used to make basic sales analysis easier through natural-language questions.

## What It Does

The assistant can:

- Read sales data from Google Sheets
- Answer questions about the data using natural language
- Analyze sales performance and generate insights
- Maintain conversation context using memory
- Send analysis and reports through email

### Example Questions

- Which product generated the highest revenue?
- Which region performed best in terms of revenue and profit?
- Analyze the sales data and give me the top 3 insights and recommendations.

## Workflow

```text
User
  ↓
Chat Trigger
  ↓
AI Agent
  ├── Google Gemini
  ├── Memory
  ├── Google Sheets → Get Data
  └── Gmail → Send Report
  ↓
Business Insights
