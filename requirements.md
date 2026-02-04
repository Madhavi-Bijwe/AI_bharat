# Requirements – ValueUnlocked

## Project Overview
ValueUnlocked is an AI-based platform designed to recognize and value informal or undocumented work experience.  
The system converts lived work experience into a structured and credible “Work Capability Profile” that can be used for employment, financial services, and institutional recognition.

---

## Problem Context
A large portion of India’s workforce performs skilled and responsible work without formal documentation such as degrees, certificates, or experience letters. Existing systems depend heavily on formal qualifications and fail to capture real-world competence. ValueUnlocked addresses this gap by using AI to interpret informal work experience and translate it into system-readable professional proof.

---

## Functional Requirements
- The system shall allow users to submit work experience through text or voice input.
- The system shall analyze tasks, responsibilities, and duration of work.
- The system shall extract skills and competencies from unstructured inputs.
- The system shall map extracted skills to standard job and skill frameworks.
- The system shall generate a structured Work Capability Profile.
- The system shall allow profiles to be shared with employers, banks, or institutions.
- The system may support peer or mentor validation of work experience.

---

## Non-Functional Requirements
- The system shall ensure data privacy and user consent.
- The system shall be explainable and transparent in AI outputs.
- The system shall support multilingual inputs.
- The system shall be scalable to handle a large number of users.
- The system shall be usable by users with low technical literacy.

---

## Technical Requirements
- Frontend: React or Flutter
- Backend: Python (FastAPI) or Node.js
- AI/NLP: Transformer-based language models
- Skill Mapping: ESCO framework or Custom Bharat Skill Graph
- Database: PostgreSQL or MongoDB
- Cloud Infrastructure: AWS / GCP / Azure
- Security: Role-based access control and data encryption

---

## System Requirements
- Internet-enabled device (mobile or desktop)
- Modern web browser or mobile application
- Stable internet connection (offline-first support optional)

---

## Assumptions & Constraints
- Users may not possess formal documents or certificates.
- Inputs may be informal, incomplete, or multilingual.
- The system provides capability assessment, not legal certification.
- AI outputs are intended to support decision-making, not replace institutions.

---

## Future Enhancements
- Integration with government skill and employment portals
- Advanced peer and institutional validation mechanisms
- Analytics dashboard for policymakers
- Offline data collection for rural deployment
