# Smart India Hackathon Workshop
# Date:16-04-2025
## Register Number:212224040302
## Name:S Sesha Raghavan
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Build an AI-powered virtual interview board room simulator that:

Conducts domain-specific interviews (technical & managerial)

Dynamically generates relevant questions based on the candidate’s profile

Scores both interview questions (for relevance to the domain) and answers (for quality and correctness)

Provides a final evaluative score to assist selection/promotion decisions



## Proposed Solution / Architecture Diagram
![ChatGPT Image Apr 16, 2025, 03_16_02 PM](https://github.com/user-attachments/assets/eef7b916-fb3b-4504-8244-7c85aebf2997)


## Use Cases
Candidate Interview Simulation
Candidates undergo a virtual interview with AI-generated and expert-curated questions.

👩‍🏫 Expert Evaluation
Experts ask questions and receive feedback on relevance to candidate’s domain.

🧠 NLP-Based Answer Evaluation
AI evaluates the candidate’s answers for correctness, depth, and coherence.

📊 Score & Suitability Report
The system compiles overall scores for easy decision-making.

📈 Post-interview Analytics
Insights on candidate performance and expert engagement trends.


## Technology Stack
Layer | Technology
Frontend | React.js, Tailwind CSS
Backend | Python (FastAPI) / Node.js
NLP & AI | OpenAI GPT-4 / HuggingFace Transformers / spaCy
Voice Processing | OpenAI Whisper / Google Speech-to-Text
Database | PostgreSQL (structured), MongoDB (unstructured)
Authentication | OAuth2 / JWT
Cloud | AWS EC2, Lambda, S3 OR Azure Blob, Azure Functions
Analytics & Dashboard | Plotly, PowerBI (optional integration)
CI/CD | GitHub Actions / Jenkins
Containerization | Docker, Kubernetes

## Dependencies
OpenAI API / HuggingFace Transformers – for question generation and response evaluation

Google Cloud Speech-to-Text / Whisper – for audio input transcription

Secure Cloud Storage – for storing interview transcripts

DRDO-specific Domain Ontologies – to tailor the question generation

Govt Cybersecurity Compliance Tools – to meet security & privacy regulations

Postgres/MongoDB Drivers – for database management
