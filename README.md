# GP1 
AI-powered delivery comparison and decision-support system that compares delivery options, predicts delivery times using Machine Learning, and provides personalized recommendations using Multi-Criteria Decision-Making (MCDM).
# Smart Delivery Comparison App

An AI-powered delivery comparison and decision-support system. It aggregates delivery options from multiple platforms, predicts actual delivery time using Machine Learning, and ranks options using Multi-Criteria Decision-Making (MCDM) based on user preferences.

## Project Status

Graduation Project I — documentation, requirements analysis, and initial system design phase.

## Team

| Member | Primary Role | Main Responsibilities |
|---|---|---|
| Jadel Alsaeri | Scrum Master | Sprint planning, coordination with the supervisor, report integration |
| Joud Alshahrani | ML / Data Lead | Data simulation, ML models, evaluation |
| Ghadah Altemyat | Backend Lead | FastAPI, MCDM engine, database design |
| Albandari Alsaadoon | Frontend & UI/UX Lead | Wireframes, Flutter interface, usability |

**Supervisor:** Dr. Ahmed Ibrahim  
**University:** Princess Nourah Bint Abdulrahman University

## Problem 

Users must manually compare prices, delivery fees, and delivery times across multiple delivery platforms. This process can be time-consuming and may lead to decision fatigue when users evaluate multiple options.

## Proposed Solution

The Smart Delivery Comparison App provides an intelligent platform for comparing delivery options across multiple services.

The proposed system includes:

- Unified comparison of delivery options
- Machine Learning regression model for delivery-time prediction
- Multi-Criteria Decision-Making (MCDM) using the Weighted Sum Model (WSM)
- Personalized ranking based on user preferences
- Deep linking to the selected delivery platform

## Tech Stack

- Flutter — Mobile Application
- React.js — Web Application
- FastAPI — Backend API
- Python — Backend and Machine Learning
- PostgreSQL — Database
- scikit-learn — Machine Learning
- XGBoost — Machine Learning

## Repository Structure
,
```text
GP1/
├── docs/       # Report, diagrams, wireframes, and survey results
├── ml/         # Data simulation, notebooks, and model training
├── backend/    # API and MCDM engine
├── web/        # React.js web application
├── mobile/     # Flutter mobile application
├── data/       # Sample datasets with no personal data
└── README.md   # Project documentation
