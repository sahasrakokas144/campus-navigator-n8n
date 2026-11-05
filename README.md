# campus-navigator-n8n
A campus navigator for SRMSP university to help students travel through campus
# 🏫 Campus Navigator – AI Campus Assistant

An AI-powered campus information assistant built using **n8n** that helps students quickly access university information through natural-language conversations.

🔗 **Live Demo:** [Campus Navigator](https://veda-08.app.n8n.cloud/assistant/fc6bf7be-0a70-4770-ada7-0c30b410e37e)

## 📌 Project Overview

Campus Navigator is designed to simplify access to campus-related information. Students can ask questions about university facilities, locations, timings, departments and contacts without manually searching through multiple websites.

The chatbot uses an AI Agent connected to a structured campus knowledge base to retrieve relevant information and generate helpful responses.

## ✨ Features

- 💬 Natural-language conversational interface
- 🏢 Campus building and facility information
- 📚 Library information
- 🧪 Laboratory and academic department information
- 🏥 Medical and health centre information
- 🏠 Hostel and dining facilities
- 📞 Important university contacts
- 🔍 Knowledge-base-driven responses
- 🛡️ Fallback responses when information is unavailable
- 🚫 Avoids inventing unverified campus information

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| AI Agent | Intelligent question answering |
| Chat Model | Natural-language understanding and response generation |
| n8n Data Tables | Structured campus knowledge storage |
| n8n Chat Interface | Student-facing chatbot |

## ⚙️ Workflow Architecture

Student Question  
↓  
Chat Trigger  
↓  
Campus Navigator AI Agent  
↓  
Chat Model + Conversation Memory  
↓  
Campus Knowledge Base Retrieval  
↓  
Relevant Information Processing  
↓  
Student-Friendly Response

## 🧠 Knowledge Base

The project uses a structured data table named `campus_knowledge_base`.

Information is organised into categories such as:

- Locations
- Timings
- Departments
- Facilities
- Contacts
- Frequently Asked Questions

The chatbot is instructed to acknowledge unavailable information instead of generating unsupported answers.

## 🧪 Testing

The chatbot was tested with 10 live questions covering:

- Library location and timings
- Academic departments
- Medical facilities
- Hostel information
- Administrative contacts
- Sports and student facilities

The tests checked knowledge retrieval, answer accuracy and fallback behaviour.

## 🚀 Deployment

The application is deployed using n8n Cloud.

**Try the chatbot:**  
https://veda-08.app.n8n.cloud/assistant/fc6bf7be-0a70-4770-ada7-0c30b410e37e

## 📂 Repository Structure

```text
campus-navigator-n8n/
│
├── README.md
├── campus-navigator.json
└── screenshots/
    ├── workflow.png
    ├── knowledge-base.png
    └── chatbot.png
```

## 🔧 How to Import the Workflow

1. Create an n8n account.
2. Open the n8n workflow editor.
3. Select Import from File.
4. Upload `campus-navigator.json`.
5. Configure the required AI model credentials.
6. Ensure the campus knowledge table is populated.
7. Test the workflow and activate it.

Note: Imported workflows may require separate configuration of credentials and data tables.

## 🎯 Future Improvements

- Expand the campus knowledge base.
- Add interactive campus navigation and maps.
- Include multilingual student support.
- Add more verified department and faculty information.
- Improve information retrieval and search accuracy.

## 👩‍💻 Project Information

**Project:** Campus Navigator  
**Platform:** n8n Cloud  
**Domain:** AI Automation / Conversational AI  
**Institution:** SRM University-AP

---

*Built to make campus information more accessible, organised and convenient for students.*
