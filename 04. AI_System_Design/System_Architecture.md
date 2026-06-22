# System Architecture – AI Recruitment Screening System

---

## Architecture Overview

The system follows a layered architecture combining AI/ML services with a recruitment decision-support platform.

---

## Architecture Style
- Layered Architecture
- Microservice-ready design (future scalability)
- AI-enhanced decision engine

---

## System Layers

### 1. Presentation Layer
- Recruiter Dashboard (Web UI)
- Hiring Manager Interface

---

### 2. Application Layer
- CV Processing Service
- Job Processing Service
- Matching Engine
- Ranking Engine

---

### 3. AI / ML Layer
- NLP-based CV Parser
- Semantic Matching Model (Embeddings)
- Scoring Algorithm Engine
- Bias Detection Module (future enhancement)

---

### 4. Data Layer
- Candidate Database
- Job Database
- Scoring & Analytics Store

---

## External Integrations
- Applicant Tracking Systems (ATS)
- Job Portals (LinkedIn, etc.)
- Email/Notification Services

---

## Key Design Principle
The system is designed as a **decision-support system**, not a fully autonomous hiring system, ensuring human oversight remains in recruitment decisions.
