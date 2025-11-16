# Seneca Marketplace – Project Charter  
**Version:** 1.0  
**Date:** October 11th, 2025  
**Project Manager** (and sponsor): Ahmad Mashal

---

## 1. Introduction

This project aims to develop **Seneca Marketplace**, a secure, campus-exclusive online platform for Seneca College students to buy and sell used textbooks, electronics, and personal items. Currently, students rely on informal communication channels such as social media or word of mouth, which leads to inefficiencies, safety concerns, and missed opportunities.  

Seneca Marketplace will centralize this process by offering verified student authentication, item listings with categories and images, secure messaging, and campus-based meet-up scheduling. The goal is to improve convenience, security, and community engagement while reducing waste and promoting reuse within the Seneca student body.

---

## 2. Overview  
### 2.1 Project Summary
Seneca Marketplace is a full-stack web application designed exclusively for Seneca College students to buy and sell used textbooks, electronics, and student essentials in a secure and convenient environment. The platform supports verified student authentication, item listings with images and categories, secure messaging between buyers and sellers, and meet-up coordination at Seneca campus locations. The system aims to improve trust, reduce risk, and provide a centralized marketplace for students.

### 2.2 Project Objectives
- The main objectives of this project are:
- Develop a responsive web application accessible from both desktop and mobile browsers.
- Implement secure user authentication using verified Seneca email credentials.
- Allow users to post, edit, and manage item listings with descriptions, categories, and photos.
- Enable buyers to search, sort, and filter listings using custom search criteria.
- Provide a built-in messaging feature to support safe buyer–seller communication.
- Include a meet-up scheduling tool using Seneca campus locations (Newnham, King, Seneca@York).
- Deploy the application using modern cloud hosting and CI/CD tools to ensure scalability and reliability.

---

## 3. Milestones  

1.	Finalize technological stack for front-end, back-end, and database.
2.	Complete authentication setup using Clerk and Firebase.
3.	Develop front-end UI with React and Tailwind CSS.
4.	Implement backend APIs with Node.js and Express.
5.	Integrate meet-up location selector and item filtering features.
6.	Conduct full system testing and deployment on Vercel (front-end) and Render (back-end).

### 3.1 Work Breakdown Structure  
<img width="938" height="696" alt="image" src="https://github.com/user-attachments/assets/7cd5261a-1b73-41ec-9f69-4bad312b9be8" />


### 3.2 Requirements Traceability Matrix  

| Req ID | Requirement                                                                                                         | Del ID | Deliverable                                               | Owner             | Status  |
|--------|---------------------------------------------------------------------------------------------------------------------|--------|-----------------------------------------------------------|-------------------|---------|
| REQ01  | Users must register and log in using verified Seneca email credentials                                             | DEL01  | Secure login and registration system with Seneca verification | Ahmad Mashal      | pending |
| REQ02  | Application must provide a responsive web UI on desktop and mobile                                                 | DEL02  | Marketplace interface for posting and browsing items      | Tajinder Kaur     | pending |
| REQ03  | Users must be able to create, edit, and delete item listings with title, description, category, price, and photos  | DEL02  | Marketplace interface for posting and browsing items      | Tajinder Kaur     | pending |
| REQ04  | Buyers must be able to search, sort, and filter listings by category, price, and keywords                          | DEL02  | Marketplace interface for posting and browsing items      | Tajinder Kaur     | pending |
| REQ05  | System must provide secure messaging between buyers and sellers within the platform                                | DEL03  | Messaging or contact system between buyers and sellers    | Ahmad Mashal      | pending |
| REQ06  | System must allow users to select a meet-up location from Seneca campuses (Newnham, King, Seneca@York)             | DEL04  | Campus meet-up location selector                          | Tajinder Kaur     | pending |
| REQ07  | System must be deployed using cloud hosting with a CI/CD pipeline for front-end and back-end                       | DEL05  | Fully deployed and tested application                     | Nizon             | pending |
| REQ08  | A formal test plan and test execution report must be created for core features (auth, listings, messaging, etc.)   | DEL06  | Test plan and test execution reports                      | Karan Preet Singh | pending |

---

## 4. Deliverables  

1. DEL01 – Secure login and registration system with Seneca verification

2. DEL02 – Marketplace interface for posting and browsing items

3. DEL03 – Messaging or contact system between buyers and sellers

4. DEL04 – Campus meet-up location selector

5. DEL05 – Fully deployed and tested application

6. DEL06 – Test plan and test execution reports for core features (auth, listings, messaging, meet-ups, etc.)

### 4.1 Gantt Chart
<img width="1836" height="779" alt="image" src="https://github.com/user-attachments/assets/98072082-2030-4eff-89c7-53307d86b614" />

The Critical Path is the longest sequence of dependent activities that determines the minimum time required to complete the project. Any delay in these tasks will directly delay the overall project completion date. The Critical Path for this project includes: Define Requirements → Design UI Mockups → Setup Project Environment → Implement Authentication → Develop Front-End → Integrate Meet-Up Selector → Add Search & Filter → Testing Phase → Deployment and Final Review. These tasks are highlighted in red in the Gantt chart.

---

## 5. Preliminary Budget  

---
### 5.0 Budget Context - Project Duration & Sprints

This academic project follows an Agile development approach with **2-week sprints**. Over a **16-week** total duration, the team will complete **8 sprints**. Since all development work is completed by students as part of the course, the sprint structure impacts timeline but **does not result in personnel costs**.

---

### 5.1 Project Team (No Personnel Charges)

| **Name**            | **Role**               | **GitHub**     | **Email**                  |
|---------------------|------------------------|----------------|----------------------------|
| Ahmad Mashal        | Back-End Developer     | AhmadMashal1   | aamashal@senecacollege.ca  |
| Nizon               | DevOps / QA Engineer   | Nizon114       | n56@myseneca.ca            |
| Tajinder Kaur       | Front-End Developer    | tkaur161       | tkaur161@myseneca.ca       |
| Karan Preet Singh   | Tester                 | kpsingh19      | kpsingh19@myseneca.ca      |

Total personnel cost: **0 CAD**

---

### 5.2 Hardware

All developers are using their own personal laptops.
Therefore, hardware cost is:

**0 CAD**

---

### 5.3 Subscriptions and Hosting Costs (Estimated for 500 Users)

These services support development, design, deployment, and cloud hosting.

#### Subscriptions
| Subscription / Service | Purpose                           | Monthly (CAD) | 4 Months (CAD) |
|------------------------|-----------------------------------|----------------|-----------------|
| Cursor Pro             | Developer productivity             | 80             | 320             |
| Figma Pro              | UI/UX design collaboration         | 80             | 320             |
| Vercel (Frontend)      | Front-end hosting & CI/CD pipeline | 20             | 80              |
| Hostinger Domain       | Domain name (1 year, $9.99 USD)    | N/A            | **14**          |

---

#### AWS Services (Backend, Auth, Storage, Scaling)  
Estimated for **500 active users**.

| AWS Service           | Purpose                                   | 4-Month Cost (CAD) |
|-----------------------|---------------------------------------------|----------------------|
| Amazon ECS            | Backend container orchestration             | 120                  |
| Amazon ECR            | Docker image storage                         | 24                   |
| Amazon Cognito        | User authentication (500 users = free)       | 0                    |
| Amazon S3             | Storage for listing images & metadata        | 16                   |
| AWS Load Balancer     | High availability & traffic routing          | 108                  |
| **Total AWS**         | —                                           | **268**              |

---

### 5.4 Overall Cost Summary

| Category            | Cost (CAD) |
|---------------------|------------|
| Subscriptions       | 720        |
| Vercel Hosting      | 80         |
| AWS Services        | 268        |
| Domain (Hostinger)  | 14         |
| **Total (4 Months)**| **1,082 CAD** |

---

### 5.5 Final Cost With Contingency

| Description               | Amount (CAD) |
|---------------------------|--------------|
| Total Estimated Cost      | 1,082        |
| Contingency (10%)         | 108.2        |
| **Final Project Cost**    | **1,190 CAD** |

---

## 6. Organization and Stakeholders  
*(To be completed in a future workshop)*  

---

## 7. Risks, Assumptions, and Constraints  
*(To be completed in a future workshop)*  
