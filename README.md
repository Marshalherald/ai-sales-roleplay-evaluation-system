# Llm-Powered-Automated-Sales-Coaching-&-Performance-Analytics
AI-powered sales roleplay evaluation system built with n8n, Vapi AI, Groq LLM, Google Sheets, and Gmail. Automatically analyzes sales conversations, scores performance, generates coaching insights, and delivers evaluation reports.
# AI Sales Roleplay Evaluation System

## Overview

The AI Sales Roleplay Evaluation System is an automation workflow that evaluates completed sales conversations and provides instant coaching feedback.

The system receives call transcripts from Vapi AI, analyzes sales performance using Groq LLM, stores evaluation data in Google Sheets, and automatically emails coaching reports to sales managers and representatives.

---

## Problem Statement

Sales managers spend significant time manually reviewing sales calls and providing feedback.

Challenges include:

- Inconsistent evaluation standards
- Delayed coaching feedback
- Limited scalability for growing sales teams
- High managerial workload

This solution automates the entire evaluation process using AI.

---

## Solution

The workflow automatically:

1. Receives completed sales calls from Vapi AI
2. Extracts and validates conversation transcripts
3. Evaluates sales performance using Groq LLM
4. Generates coaching recommendations
5. Stores results in Google Sheets
6. Sends evaluation reports via email
7. Alerts administrators if failures occur

---

## Architecture

Vapi AI
↓
Webhook
↓
Transcript Processing
↓
Groq LLM Evaluation
↓
Response Parsing
↓
Google Sheets Database
↓
Email Reporting

---

## Evaluation Criteria

The AI evaluates sales representatives on:

- Rapport Building
- Discovery
- Qualification
- Value Communication
- Objection Handling
- Closing Skills

Each category receives a score between 0 and 100.

---

## Features

### Automated Call Analysis

Automatically evaluates completed conversations without human intervention.

### AI Coaching Insights

Provides:

- Strengths
- Weaknesses
- Missed Opportunities
- Coaching Recommendations

### Performance Tracking

Stores evaluation history for future reporting and trend analysis.

### Real-Time Reporting

Delivers detailed evaluation reports immediately after call completion.

### Failure Monitoring

Sends automated alerts when AI evaluation fails.

---

## Tech Stack

- n8n
- Vapi AI
- Groq LLM
- Google Sheets
- Gmail API

---

## Workflow Nodes

![Screenshot of the n8n workflow.]()

---

## Business Impact

### Reduced Coaching Time

Automates manual call reviews and feedback generation.

### Faster Learning Cycles

Sales reps receive instant performance feedback.

### Scalable Evaluation

Supports large sales teams without additional management overhead.

### Data-Driven Coaching

Provides consistent evaluation standards across all representatives.

---

## Future Enhancements

- CRM Integration
- Leaderboards
- Weekly Performance Reports
- Team Performance Analytics Dashboard
- Slack Notifications
- Multi-Language Support

---

## Author

Farah Naaz Ali

B.Tech CSE (AI & ML)
Sister Nivedita University
