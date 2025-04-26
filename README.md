# Shopify Automation Using ServiceNow

🚀 **Project Overview**

This project demonstrates how ServiceNow can be used as an orchestration engine to automate content publishing workflows across multiple platforms after a new article is published on Shopify.

---

## 🛠️ Key Technologies Used

- ServiceNow (Washington DC Release)
- Shopify Webhooks
- OpenAI (GPT API) for title and description generation
- Canva API for social media design creation
- REST API Integrations
- ServiceNow Flow Designer and Scripted REST APIs
- IntegrationHub (optional, low-code extensions)

---

## 📋 Workflow Overview

1. **Shopify Event**: New article published ➔ Webhook triggers ServiceNow
2. **ServiceNow Flow**:
   - Calls OpenAI GPT to create engaging social titles and descriptions
   - Calls Canva API to auto-generate social media designs
   - Composes social media posts
3. **Posting Automation**:
   - Posts the content to Twitter (X), LinkedIn, and Instagram via their APIs
4. **Tracking**:
   - Updates the record in ServiceNow (status = Posted)
   - Saves links to published posts

---

## 🧩 Architecture Diagram

*(Coming soon: Visual diagram showing Webhooks, REST calls, Flows, and API interactions.)*

---

## 📂 Repository Structure

| Folder/File | Purpose |
|:------------|:--------|
| `flow_design.md` | Detailed flow logic and decision trees |
| `architecture.png` | Visual architecture of the solution |
| `api_scripts/` | Example RESTMessageV2 scripts for each integration |
| `README.md` | This document |

---

## 📈 Future Enhancements

- Engagement tracking from social media APIs
- Auto-generate marketing reports
- Integration with CRM (e.g., Salesforce) for campaign performance
- Full ServiceNow dashboards for marketing managers

---

## ✨ Why This Project Matters

This project shows how ServiceNow can power intelligent, multi-system automation — going far beyond traditional ITSM.  
It demonstrates API orchestration, real-world event handling, and AI-driven content workflows in a modern business scenario.

---
