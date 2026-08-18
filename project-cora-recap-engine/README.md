# Cora Recap Engine

## Project Overview

This application automates lead management and recap processes, streamlining operations for businesses handling numerous inbound and outbound leads. By enhancing efficiency, it allows teams to focus more on strategic activities rather than administrative tasks. 

A key design decision was the integration of AI capabilities using OpenAI, which not only improves the accuracy of lead assessments but also generates insightful recaps, ensuring that users have the most relevant information at their fingertips.

---

## Business Problem

The Cora Recap Engine addresses the challenge of managing and automating lead processes for businesses, particularly those handling inbound and outbound leads. It streamlines recap workflows, reducing manual effort and improving efficiency for sales teams.

---

## Objective

- Automate lead management and recap processes to enhance operational efficiency.
- Integrate AI capabilities for generating summaries and insights from lead interactions.
- Provide a reliable API service to replace complex workflows like those offered by Zapier.

---

## Tools & Technologies

- FastAPI
- PostgreSQL
- Redis
- RQ
- OpenAI
- SQLAlchemy
- Docker
- Pydantic

---

## Project Workflow

- The API service receives lead data through webhooks and processes it using FastAPI.
- Data is stored persistently in PostgreSQL, ensuring authoritative state management.
- The worker service utilizes RQ to handle background job execution for processing leads.
- AI-driven summaries are generated using OpenAI, enhancing the quality of recaps.
- The system integrates with external services like GHL for CRM updates and Synthflow for callback scheduling.

---

## Key Insights

- By using PostgreSQL as the authoritative state store, the system ensures data integrity and reliability across multiple components.
- The integration of OpenAI for AI analysis allows for automated insights, reducing the manual workload for sales teams.
- Containerized deployment with Docker facilitates easy scalability and consistent environments across development and production.

---

## Final Dashboard / Project Preview

No project preview image available.

---

## Business Impact

- Enhanced efficiency in lead management processes, allowing teams to focus on higher-value tasks.
- Demonstrated capability in managing complex system architectures with multiple integrated components.
- Showcased practical AI engineering skills in a production-grade application, highlighting readiness for real-world challenges.

---

[← Back to portfolio](../README.md)
