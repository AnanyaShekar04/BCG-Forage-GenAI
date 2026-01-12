# Financial Analysis & AI Chatbot  (BCG Simulation)

This repo contains my submission for the **BCG GenAI Job Simulation**. The project focuses on two main tasks: analyzing real-world financial data and building a rule-based AI chatbot to make that data accessible.

##  Project Overview

The goal was to simulate the role of a Junior Data Scientist helping a client (Global Finance Corp) understand their financial performance. Instead of just looking at spreadsheets, I built a prototype tool that allows users to query financial metrics using natural language.

### Task 1: Financial Data Analysis 
I started by manually extracting key financial figures (Revenue, Net Income, Assets, Liabilities, Cash Flow) from the 10-K filings of **Microsoft**, **Tesla**, and **Apple** for the last three fiscal years.

**What I did:**
* Cleaned and structured the data using **Pandas**.
* Calculated year-over-year (YoY) growth rates to spot trends.
* **Key Insight:** I found that while Tesla had massive growth spikes in 2022 (>50%), Microsoft has shown the most consistent, steady profitability in the most recent fiscal year.

### Task 2: Building the Chatbot 
Once the data was ready, I developed a simple AI chatbot in Python to interact with it.

**How it works:**
* It's a rule-based chatbot (no LLMs yet!) that scans user input for keywords.
* It identifies the **Company** (e.g., "Apple") and the **Metric** (e.g., "Net Income").
* It returns a formatted response with the exact figure from the dataset.

##  Tech Stack
* **Python 3**
* **Pandas** (for data manipulation)
* **Jupyter Notebook** (for development and testing)

