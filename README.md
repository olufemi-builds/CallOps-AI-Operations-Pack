# CallOps AI Operations Pack

## Overview

CallOps AI Operations Pack is an AI-powered operational assistant built using Microsoft Copilot Studio and Power Automate.

The solution enables call center supervisors and operations managers to retrieve queue-specific KPI metrics through natural language conversations.

Users can request operational information for queues such as Billing, Claims, Refunds, Sales, Technical Support, VIP Support, and New Accounts, and receive instant KPI reports.

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


echnologies Used
Microsoft Copilot Studio
Power Automate
Excel Online (Business)
OneDrive for Business
Microsoft 365
Power Fx
Dataset
The KPI dataset used in this solution is stored in the /data folder of this repository.
It includes:
Queue Name
Wait Time
CSAT
Abandonment Rate
Available Agents
Daily Call Volume
Operational Status
Screenshots
This repository includes the following visuals:
Copilot Studio agent conversation flow
Power Automate workflow execution
Excel KPI dataset table
Billing queue output example
Claims queue output example
VIP Support output example
Demo Video
A short demonstration of the agent in action:
👉 [Insert your video link here]
Solution Components
Copilot Studio
Conversational AI interface
User input capture
Queue selection handling
KPI report presentation
Power Automate
Receives queue name from Copilot Studio
Reads data from Excel Online
Filters records by queue name
Returns KPI metrics to Copilot Studio
Excel Online
Stores operational KPI data:
Queue Name
Wait Time
CSAT
Abandonment Rate
Available Agents
Daily Call Volume
Status
Setup Instructions
Prerequisites
Microsoft Copilot Studio
Power Automate
Microsoft 365 account
Excel Online (Business)
OneDrive for Business
Steps
Create KPI dataset in Excel Online
Store workbook in OneDrive for Business
Create Copilot Studio agent
Build Power Automate flow triggered by Copilot Studio
Add the following actions:
List Rows Present in a Table
Filter Array
Compose
Return Values to Copilot Studio
Connect flow to Copilot Studio topic
Publish the agent
Test with queues like Billing, Claims, Refunds, Sales, VIP Support
Technical Highlights
End-to-end Microsoft ecosystem integration
Low-code AI automation solution
Dynamic queue-based filtering logic
Conversational operational intelligence
Real-time KPI retrieval
Seamless Copilot Studio + Power Automate integration
Challenges and Learnings
The main challenge was ensuring correct data mapping between Power Automate and Copilot Studio, especially handling filtered Excel outputs.
Key learnings include:
Designing conversational AI workflows
Power Automate orchestration
Excel Online integration patterns
Variable handling in Copilot Studio
Low-code enterprise automation design
Microsoft AI ecosystem integration
Future Enhancements
AI-powered KPI health scoring
Power BI dashboard integration
Trend and forecasting analysis
Multi-queue comparison mode
Automated escalation workflows
Intelligent operational recommendations
Hackathon Information
Track: Operative
Project Name: CallOps AI Operations Pack
Built With: Microsoft Copilot Studio, Power Automate, Excel Online (Business)
Purpose: Provide conversational operational intelligence for call center supervisors and managers.
Author
Olufemi Olamoyegun
FMVA, FAIMFIN
Microsoft Power BI & Fabric Analyst Certified
AI-Driven Finance Educator
License
This project was created for the Microsoft Agent Academy Live Hackathon 2026.
