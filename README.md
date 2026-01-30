# AI-mock-interview-invitation

# 🧠 AI Mock Interview Automation System

An end-to-end AI-powered mock interview automation platform built using **n8n, OpenAI, Google Sheets and Gmail** that simulates a real recruitment interview pipeline with **role-based interview agents, persistent candidate tracking and automated interview emails**.

This project demonstrates how AI can be embedded into real operational workflows — not just used as a standalone chatbot.

---

## 🎥 Demo

**Full Demo Video**  
👉 https://drive.google.com/file/d/18sFkJr3zZ4DA5Vhd2jX_-FejCI5uhzpv/view?usp=sharing

Workflow: 
<img width="1913" height="1036" alt="image" src="https://github.com/user-attachments/assets/1879cde3-84c8-419b-90b9-d2e9b4ec8aa1" />

Output:
<img width="1911" height="1029" alt="image" src="https://github.com/user-attachments/assets/eb7bdfcb-1e49-4a05-b8f9-d6de7c132ac7" />

Email:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a068984-2621-4ce1-9aeb-a6054e998a42" />

Video Interview:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c876befa-3a0f-45b3-a6aa-70e279cfce09" />

---

## 🚀 Project Overview

The AI Mock Interview Automation System automates the complete mock interview lifecycle.

Once a candidate submits their information, the system:

- Automatically initializes an AI interview agent
- Configures the interview context based on role and experience
- Stores structured candidate data
- Sends a personalized interview continuation email
- Allows the candidate to resume the interview at any time

In simple words:

**Candidate submits → AI interviewer is prepared → data is stored → email is sent → interview continues automatically.**

---

## 🎯 What Problem This Project Solves

Most mock interview platforms:

- Ask static and generic questions  
- Do not store structured interview data  
- Require manual setup or scheduling  
- Do not support interview continuation  
- Provide limited personalization  

This system solves all of the above by automating the entire interview workflow.

---

## 🧩 Key Features

- AI interview agent initialized per candidate
- Role-based and experience-based interview configuration
- Persistent candidate storage in Google Sheets
- Automated personalized interview emails
- Resume interview capability
- Workflow branching and routing using n8n
- Structured data formatting using JavaScript nodes
- Fully automated pipeline with no human intervention

---

## 🏗️ System Architecture

**Main Components**

- Google Form – Candidate data collection
- n8n – Workflow orchestration engine
- OpenAI – Interview agent and question generation
- Google Sheets – Persistent candidate database
- Gmail – Automated interview continuation emails

---

## 🔁 Workflow Logic

1. Candidate submits details through Google Form  
2. Google Form triggers an n8n webhook  
3. A new AI interview agent is initialized dynamically  
4. Candidate profile and interview configuration are saved in Google Sheets  
5. JavaScript nodes format structured interview data  
6. A personalized interview email is generated  
7. Gmail sends the interview continuation email  
8. Candidate resumes the interview from the last stored state  

The entire workflow runs automatically.

---

## 🧠 Engineering Highlights

- Dynamic AI agent context creation per candidate
- Role-based interview routing logic
- Persistent interview state handling
- Fully automated email personalization
- Real-time workflow orchestration using n8n
- Designed as an automation pipeline, not a simple chatbot

**This is automation engineering, not just prompt usage.**

---

## 📂 Repository Structure

ai-mock-interview-automation/
│
├── n8n-workflow/ # Exported n8n workflow JSON
├── screenshots/ # Workflow and output screenshots
├── docs/ # Architecture and setup documents
└── README.md


*(Folder structure can be adjusted based on your actual repository files.)*

---

## ⚙️ Tech Stack

- n8n
- OpenAI API
- Google Forms
- Google Sheets API
- Gmail API
- JavaScript (inside n8n code nodes)

---

## 🛠️ Setup Instructions (High Level)

1. Create a Google Form for candidate submission  
2. Deploy n8n (local or cloud)  
3. Create a webhook node in n8n  
4. Connect Google Sheets and Gmail credentials  
5. Configure OpenAI credentials in n8n  
6. Import the provided n8n workflow JSON  
7. Update Sheet ID, Form fields and email template  
8. Activate the workflow  

Once activated, the system runs fully automatically.

---

## 📌 Use Cases

- Interview preparation platforms
- EdTech applications
- HR automation tools
- AI-driven recruitment experiments
- Internal hiring and training simulations

---

## 🔮 Future Enhancements

- Automated interview scoring and skill evaluation
- Interview transcript analytics
- Recruiter / trainer dashboard
- Multi-round interview workflows
- Resume parsing and skill mapping

---

## 🏷️ Topics

ai
automation
n8n
openai
ai-agent
mock-interview
workflow-automation
hr-tech
edtech
recruitment-automation
gmail-api
google-sheets


---

## 👤 Author

**Rohit Bachchhe**  
AI / ML Engineer – Automation & AI Workflow Systems

