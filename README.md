# Smart India Hackathon Workshop
# Date: 13.03.2025
## Register Number: 212224040223
## Name: Nishanth R S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The core idea is to build an advanced, immersive virtual interview platform that replicates a board room environment. This solution is designed for DRDO’s Recruitment and Assessment Centre (RAC) to conduct unbiased, objective, and interactive interviews. Key points include:

Real-World Simulation:
An environment that mimics a physical board room experience, complete with ice-breaking sessions and progressively challenging techno-managerial questions.

Objective Assessment:
Utilizing AI and Natural Language Processing (NLP) to dynamically generate questions and to score both the expert’s questions and the candidate’s responses for relevance and depth.

Quantifiable Metrics:
A scoring system that not only assesses the subject knowledge of candidates but also provides feedback on the relevancy of questions, ensuring that interviews are aligned with the candidate’s expertise.

Continuous Feedback Loop:
Detailed post-interview reports enable both candidates and interviewers to understand performance metrics, thereby facilitating continuous improvement in the recruitment process.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/815ee4c2-54d1-4bcb-a751-ec41645d2a7f)


## Use Cases
1. Applicant (Candidate)
The applicant is the user who takes part in the interview process.

Use Cases:
Register & Login

The applicant signs up and logs into the system.
Credentials are authenticated for security.
Join Simulated Interview

The system schedules and initiates a virtual interview session.
The applicant enters the simulation interface.
Answer AI-Generated Questions

The system asks pre-configured or AI-generated interview questions.
Questions range from general, technical, and behavioral to managerial, depending on the role.
Receive Instant Feedback

The AI evaluates responses based on pre-trained NLP models.
The system provides real-time feedback and initial scoring.
View Performance Report

A detailed report is generated highlighting strengths and weaknesses.
The applicant can review answers and suggestions for improvement.
2. Selector (Recruiter/Interviewer)
The selector is responsible for reviewing applicants and their responses.

Use Cases:
Create & Customize Interview Questions

The selector can input or modify questions for different interview stages.
AI-based suggestions can help refine questions.
Monitor Applicant Responses

The selector views candidate responses in real-time or after the session.
Can add manual comments or ratings.
Evaluate Responses & Score

The selector assigns manual scores (if needed) in addition to AI scoring.
Can adjust AI evaluation criteria for fairness.
Access AI-Based Analysis

The system generates in-depth analytics on candidate performance.
Comparison reports between different candidates.
3. Admin (System Administrator)
The admin manages the software platform, user roles, and overall system performance.

Use Cases:
Manage Users & Permissions

Admin adds, removes, or updates users (applicants and selectors).
Defines roles and access permissions.
Configure AI Evaluation Rules

Admin fine-tunes AI scoring parameters to align with hiring policies.
Adjusts weightage for different question categories.
Generate Reports & Insights

Creates detailed system-wide performance reports.
Identifies trends in candidate performance and interview efficiency.
Workflow Summary
Applicant registers & logs in.
Applicant takes the interview, answering AI-generated questions.
AI scores responses & provides instant feedback.
Selector reviews & refines scoring.
Admin manages configurations & generates reports.


## Technology Stack
Front-End:
Frameworks: React, Angular, or Vue.js for building dynamic user interfaces.

Back-End:
Programming Languages: Python (Django/Flask), Node.js, or Java (Spring Boot) for server-side logic.
API Design: RESTful APIs or GraphQL for communication between front-end and back-end modules.

AI & NLP:
Libraries & Frameworks:
NLP: spaCy, NLTK, or Hugging Face Transformers for natural language understanding.
Machine Learning: TensorFlow or PyTorch for developing and fine-tuning scoring algorithms.
Real-Time Processing: Microservices architecture to support scalable, real-time analytics.

Database:
Relational: PostgreSQL or MySQL for structured candidate and interview data.
NoSQL: MongoDB or Cassandra for storing unstructured data such as interview transcripts and logs.

DevOps & Cloud:
Containerization: Docker and Kubernetes for deployment and scaling.
Cloud Services: AWS, Azure, or Google Cloud Platform for hosting, storage, and computing needs.
CI/CD Pipelines: Jenkins, GitLab CI/CD, or similar for continuous integration and delivery.

Security & Compliance:
Data Security: Encryption protocols for data in transit and at rest.
Access Control: Role-based access control (RBAC) to manage permissions for candidates, experts, and administrators.

## Dependencies
Successful implementation of this solution depends on several key factors:

Integration with Existing Systems:

HR & DRDO Databases: Seamless integration with existing candidate profiles, expert directories, and recruitment management systems.
Authentication Services: Use of existing Single Sign-On (SSO) or authentication protocols to ensure secure access.
Third-Party APIs & Services:

Video Conferencing: Dependence on reliable video streaming and real-time communication APIs.
Cloud Infrastructure: Dependence on cloud service providers for scalable computing resources and data storage.
Data Quality & Training:

Training Data for AI/NLP: Availability of high-quality training data to fine-tune AI algorithms for assessing relevance and subject mastery.
Feedback Loops: Continuous data feedback from interviews to further refine scoring algorithms.
Regulatory & Security Compliance:

Data Privacy Regulations: Compliance with national and international data protection laws.
Security Standards: Adherence to best practices in cybersecurity to protect sensitive candidate and expert data.
User Adoption & Training:

Stakeholder Buy-In: Training for both candidates and experts on how to effectively use the system.
Change Management: Processes to ensure smooth transition and adoption across all levels of the organization.
