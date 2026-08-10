# Cora Recap Engine

## Project Overview

Automates lead recap processes and integrates services to streamline lead management.

---

## Business Problem

The Cora Recap Engine automates lead recap processes for sales teams, allowing them to efficiently manage inbound and outbound leads. This tool is designed for organizations that need to streamline their lead management and improve communication with potential clients.

---

## Objective

- Automate the recap process for inbound and outbound leads.
- Integrate multiple services to enhance lead management efficiency.
- Provide AI-generated summaries to support sales teams in their outreach efforts.

---

## Tools & Technologies

- FastAPI
- PostgreSQL
- Redis
- RQ
- OpenAI
- SQLAlchemy
- Docker
- Python

---

## Project Workflow

- Sales teams send lead information through webhooks to the API service.
- The API processes requests and stores lead data in PostgreSQL.
- Background jobs are queued in Redis using RQ for processing tasks like AI analysis and lead updates.
- AI-generated summaries are created using OpenAI and stored for future reference.
- The system updates the CRM and schedules callbacks as needed.

---

## Key Insights

- Utilized a persistent PostgreSQL database to ensure reliable state management across lead interactions.
- Implemented a high-performance caching layer with Redis to optimize job execution and reduce latency.
- Demonstrated effective integration of AI capabilities to enhance lead summaries, improving the quality of sales outreach.
- Managed complex interactions across 11 interconnected components, showcasing strong architectural design skills.

---

## Final Dashboard / Project Preview

No project preview image available.

---

## Business Impact

- Enabled sales teams to save time and reduce manual effort in lead management.
- Improved the accuracy and relevance of lead recaps through AI-generated insights.
- Showcased advanced technical skills in building a scalable and efficient API service.

---

[← Back to portfolio](../README.md)
