# CallOps AI Operations Pack
---
## Overview
CallOps AI Operations Pack is an AI-powered operational assistant built using Microsoft Copilot Studio and Power Automate.
The solution enables call center supervisors and operations managers to retrieve queue-specific KPI metrics through natural language conversations.
Users can request operational information for queues such as Billing, Claims, Refunds, Sales, Technical Support, VIP Support, and New Accounts and receive instant KPI reports.
---
## Problem Statement
Call center leaders often need immediate access to operational performance metrics to make informed staffing and service decisions.
Traditional reporting processes require navigating dashboards, reports, or spreadsheets, creating delays in decision-making.
CallOps AI Operations Pack solves this by providing a conversational AI interface that retrieves operational KPI data instantly using natural language.
---
## Features
- Conversational KPI retrieval  
- Queue-specific reporting  
- Dynamic Excel data lookup  
- Operational status reporting  
- Power Automate workflow integration  
- Microsoft Copilot Studio agent experience  
- Natural language interaction  
- Real-time operational insights  
---
## Architecture
```text
User Input
   ↓
Microsoft Copilot Studio (Agent)
   ↓
Power Automate Flow
   ↓
Excel Online (Business Data Source)
   ↓
Filter Queue Record
   ↓
Extract KPI Metrics
   ↓
Return Operational Report to User
```
---
## Technologies Used
- Microsoft Copilot Studio
- Power Automate
- Excel Online (Business)
- OneDrive for Business
- Microsoft 365
- Power Fx
---
## Dataset
The KPI dataset is stored in the `/data` folder.
It contains:
- Queue Name
- Wait Time
- CSAT
- Abandonment Rate
- Available Agents
- Daily Call Volume
- Status
---
## Screenshots
This repository includes:
- Copilot Studio agent flow
- Power Automate workflow
- Excel KPI dataset
- Billing queue output
- Claims queue output
- VIP Support output
---
## 🎥 Demo Video

### ▶ Click below to watch the live demo

[![CallOps AI Operations Pack – Full Demo](https://img.youtube.com/vi/qxK3L4WaC7k/maxresdefault.jpg)](https://youtu.be/qxK3L4WaC7k)

---
## Solution Components
### Copilot Studio
- Conversational interface
- User input capture
- Queue selection
- KPI response display
### Power Automate
- Receives queue name
- Reads Excel dataset
- Filters matching record
- Returns KPI values
### Excel Online
- Stores operational KPI dataset
- Provides structured data for automation
---
## Setup Instructions
### Requirements
- Microsoft Copilot Studio
- Power Automate
- Excel Online (Business)
- Microsoft 365
- OneDrive
---
### Steps
1. Create KPI dataset in Excel
2. Store file in OneDrive
3. Build Copilot Studio agent
4. Create Power Automate flow
5. Add:
   - List rows in table
   - Filter array
   - Compose
   - Return response
6. Connect flow to Copilot topic
7. Publish agent
8. Test with queues like Billing, Claims, Refunds, VIP Support
---
## Technical Highlights
- End-to-end Microsoft ecosystem integration
- Natural language KPI retrieval
- Dynamic queue filtering logic
- Real-time operational reporting
- Low-code automation design
- Copilot Studio + Power Automate integration
---
## Challenges and Learnings
Main challenge was ensuring correct mapping of filtered Excel data into Copilot Studio responses.
Key learnings:
- Building conversational AI agents
- Power Automate orchestration
- Excel Online integration
- Variable passing between systems
- Low-code enterprise automation design
---
## Future Enhancements
- AI-driven KPI health scoring
- Power BI dashboard integration
- Trend analysis and forecasting
- Multi-queue comparison
- Automated escalation workflows
---
## Hackathon Information
- **Track:** Operative  
- **Project:** CallOps AI Operations Pack  
- **Built With:** Copilot Studio, Power Automate, Excel Online  
---
## Author
Olufemi Olamoyegun  
Microsoft Power BI & Fabric Analyst Certified  
---
## License
Built for Microsoft Agent Academy Live Hackathon 2026.
