# AI-Agent-For-Digital-Financial-Literacy

IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the capstone project completed during the IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies. The program is a joint initiative by Edunet Foundation, AICTE, and IBM SkillsBuild to enhance technical and professional skills in emerging technologies.

The primary objective of the internship was to provide hands-on experience in building solutions using IBM Cloud services and AI tools. Participants applied their knowledge to solve real-world challenges through capstone projects.

📝 Table of Contents
👨‍💻 Intern Details

📖 About the Internship

💡 Project: AI Agent for Digital Financial Literacy

Problem Statement

Solution Overview

⚙️ Technology Stack

🚀 Project Workflow

📊 Results

📁 Repository Contents

👨‍💻 Intern Details
Name: Maulik Thakur
Institute: Rungta College of Engineering and Technology
Department: Artificial Intelligence and Machine Learning
Duration: 4 Weeks (15th July 2025 to 7th August 2025)

📖 About the Internship
This 4-week virtual internship provided immersive learning in Artificial Intelligence, Cloud Computing, and IBM Technologies. Key components of the program included:

Week 1: Internship Orientation, IBM Cloud Introduction, IBM SkillsBuild platform navigation, and AI fundamentals
Week 2: Data handling, language models, RAG (Retrieval-Augmented Generation), and Watson NLP
Week 3–4: Capstone project development, cloud deployment, and model integration using IBM services

Completion criteria included:

Attending weekly sessions

Completing IBM SkillsBuild courses

Submitting a working project with a presentation

This internship was non-stipendiary and focused purely on skill development.

💡 Project: AI Agent for Digital Financial Literacy
🎯 Problem Statement
Digital financial tools like UPI, online banking, and personal finance apps are becoming essential, but millions of users—especially from rural or underprivileged backgrounds—lack awareness and confidence in using them. Language barriers, financial jargon, and fear of online fraud make the adoption of digital finance tools difficult.

✅ Solution Overview
An AI-driven multilingual assistant, built using Retrieval-Augmented Generation (RAG), empowers users with accurate financial information sourced from reliable portals. The system allows users to ask questions such as:

“What is UPI and how do I use it?”

“How to avoid loan fraud?”

“What interest rate is safe for a personal loan?”

It promotes financial literacy through secure, culturally sensitive interactions in the user’s preferred language.

⚙️ Technology Stack
Cloud Platform: IBM Cloud Lite

AI Model: IBM Granite via LangChain

NLP Tool: IBM Watson NLP

Backend: Python, FastAPI

Data Storage: IBM Cloudant / MongoDB

Libraries & Tools:

LangChain

Transformers

ibm-watson

Flask / FastAPI

HuggingFace RAG (optional integration)

Docker

🚀 Project Workflow
User Query Input:
The user types a question in their preferred language (e.g., Hindi, English).

Content Retrieval (RAG):
IBM Granite + LangChain fetches contextual data from pre-approved government and financial sources (RBI, NPCI, etc.)

Answer Generation:
Retrieved content is passed through the LLM to generate a simplified, trustworthy response.

Language Translation:
IBM Watson NLU enables multilingual interaction with support for regional languages.

Deployment:
The AI agent is deployed via IBM Cloud using FastAPI and Docker, exposing a REST API for web or mobile integration.

📊 Results
The agent was able to retrieve and explain financial terms with 90%+ accuracy based on mock testing.

Supported multilingual interactions in both English and Hindi.

Helped users understand safe practices and avoid online financial scams.

Response generation time: ~2.5 seconds (average)

Confidence score added to each response

