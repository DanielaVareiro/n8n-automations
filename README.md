# 🤖 n8n Automation Workflows # n8n-automações

Welcome to my repository of automation workflows and AI agents built with n8n! Here, I organize the projects I develop to solve real-world business and productivity challenges

Professional automation workflows developed in **n8n** by a certified specialist | Certificado em **n8n** Workflows otimizados para eficiência operacional e integração de sistemas

## 📋 About

Certified n8n specialist sharing optimized workflows for:
- ✅ Process automation
- ✅ API integrations
- ✅ Operational efficiency
- ✅ Scalable solutions

## 🎓 Credentials
- **n8n Certified** - [Visualizar Certificado](./Certificado%20n8n%20HashtagTreinamentos.pdf)

## 📂 Workflows
- **#1** - 📄 Automated AI Invoice Parser & Drive Archiver // Leitor Automático de Faturas com IA & Arquivador no Drive
- **#2** - 🤖 Automated AI Agent Email Assistant  // Agente de IA assistente de email
- **#3** - 💰 Refund Request Processor // Processador de análises de reembolso


## 📂 Projects

### 1. 📄 Automated AI Invoice Parser & Drive Archiver
> **Description:** An AI agent designed to automatically read invoices received via email, classify them intelligently, and archive them in an organized manner.

* **How It Works:** The workflow monitors a Gmail inbox. Upon detecting an email with an invoice attachment, an AI analyzes the document, extracts key data (amounts, dates, vendor), and classifies it (personal or corporate). The file is then saved structurally in Google Drive, and the extracted data is automatically registered in a Google Sheets spreadsheet.
* **Tech Stack:** n8n, AI Agent(OpenRouter), Gmail, Google Drive, Google Sheets, Loop Over, If's Routes.
* **Workflow File:** [Access JSON file](./workflows/Automated%20AI%20Invoice%20Parser%20%26%20Drive%20Archiver.json)

---

### 2. 🤖 Automated AI Agent Email Assistent
> **Description:** An AI that answers emails from the company's customers, providing detailed information in response to any type of question about the company.

* **How It Works:** The automation is triggered when a message arrives in the corporate email inbox; the AI ​​agent prepares a well-crafted response and automatically sends it to the customer.
* **Tech Stack:** n8n, AI Agent(Grok), Memory Agent, Gmail, If's Routes.
* **Workflow File:** [Access JSON file](./workflows/Automated&20AI&20Agent&20Email&20Assistent.json)

---

### 3. 💸 Refund Request Processor
> **Description:** an AI agent that analyzes reimbursement requests alongside data on the person registered as the company's customer.

* **How It Works:** The process is triggered by a refund request submitted via a company form; upon receiving the request, the AI ​​Agent evaluates its eligibility based on company refund policies and checks the requester's details in a Google Sheet. These details influence the agent's response, and in extreme cases, the company team is notified of the situation.
* **Tech Stack:** n8n, Webhook, Google Sheets, Gmail, Telegram, Reimbursement Form, If's Routes.
* **Workflow File:** [Access JSON file](./workflows/Refund%20Request%20Processor.json)
