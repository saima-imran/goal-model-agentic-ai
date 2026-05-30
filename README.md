Goal Model Visualiser for Agentic AI Systems
Author: Saima Imran

Date: May 2026

GitHub: github.com/saima-imran
Context: Learning Project

Research Question
How do we make the goals and intentions of agentic AI systems explicit, observable, and systematically verifiable?

Goal Types
Goal: Functional Requirement — binary (done or not done)
Softgoal: Non-Functional Requirement — satisficed (good enough)
Task: Concrete action to perform
Resource: Input or output needed
Use Case: Hospital Appointment Manager
4-agent agentic AI system managing hospital appointments in Sweden.

Agents:

Scheduling Agent: Books and optimises appointments
Monitoring Agent: Verifies scheduling intentions
Communication Agent: Notifies patients and doctors
Compliance Agent: EU AI Act and GDPR compliance
Key Finding
Traditional monitoring: 0 violations — system appears healthy.

Intentional monitoring: 8 out of 17 goals not meeting stated intentions.

The gap is completely invisible without intentional monitoring.

Biggest Intention Gaps
Balance Clinician Workload: Intended 0.8, Actual 0.61, Gap -23.8%
Send Reminders 24h Before: Intended 95%, Actual 78%, Gap -17.0
Minimise Waiting Time: Intended 5 days, Actual 4.2 days
Notify All Stakeholders: Intended 100%, Actual 87%, Gap -13.0
How to Run
Open Google Colab
Upload GoalModel_AgenticAI_SaimaImran.ipynb
Click Runtime then Run all
All outputs generated automatically
Limitations and Future Work
Goal models manually defined Future: auto-generate from AI system specifications

Monitoring uses simulated values Future: connect to real agentic AI systems

Single-level goal decomposition Future: multi-level hierarchical goal models

No conflict detection between agent goals Future: detect when agent intentions conflict

EU AI Act Connection
Article 13: Transparency requirements
Article 14: Human oversight of high-risk AI systems
Technical Stack
Python 3
matplotlib: visualisation
networkx: goal tree structure
numpy: satisfaction scoring
Google Colab: execution environment
Author
Saima Imran PhD Applicant — Intentional Monitoring of Agentic AI Software Chalmers University of Technology, Gothenburg github.com/saima-imran saimaimran4822@hotmail.com
