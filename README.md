# 🤖 Financial Trading Multi-Agent Framework

A multi-agent AI system built using **CrewAI** that analyzes stock market data, 
builds trading strategies, plans trade execution, and assesses risks.  
This framework simulates a complete trading decision pipeline using four specialized agents.

---

## 🚀 Features

- 📊 **Market Analysis** using real-time news & web scraping  
- 🧠 **Strategy generation** based on risk tolerance  
- 🕒 **Execution planning** with optimal buy/sell timing  
- ⚠️ **Risk analysis** to protect capital  
- 🧩 **Hierarchical agent process** for clean, logical workflows  
- 🔍 Uses **SerperDevTool** for web search & **ScrapeWebsiteTool** for scraping  
- 🤖 Powered by **gpt-4o-mini** as the Manager LLM  

---

## 🧠 Agents Overview

### 1️⃣ Data Analyst Agent (Market Watcher)
- Monitors live market data  
- Analyzes trends, momentum, and news  
- Provides insights on selected stocks  

### 2️⃣ Trading Strategy Developer (Planner)
- Creates trading strategies  
- Aligns strategy with user’s risk tolerance  
- Uses insights from the Data Analyst  

### 3️⃣ Trade Advisor (Execution Expert)
- Provides buy/sell timing  
- Suggests price levels and execution methods  
- Optimizes trades for best outcomes  

### 4️⃣ Risk Advisor (Safety Officer)
- Evaluates all risks  
- Warns about volatility or negative trends  
- Suggests stop-loss, risk limits, and mitigation steps  

---

## 🏗 System Architecture (Hierarchical Process)

