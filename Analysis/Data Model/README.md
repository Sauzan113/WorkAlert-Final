# Data Model – WorkAlert

## Core Entities (Entity Relationship Diagram)
* **USER:** Stores shared account credentials, role (`seeker` or `employer`), contact details, and location coordinates.
* **JOB_POSTING:** Stores job title, description, pay rate, location, status (`open`/`closed`), and `employer_id` foreign key.
* **APPLICATION:** Tracks job applications linking a `seeker_id` to a `job_id`, application status, and timestamp.
* **MESSAGE:** Stores direct communication threads between applicants and employers linked to a `job_id` or `application_id`.

## ERD Diagram
* *(Upload your Logical Entity Relationship Diagram image/PDF file into this folder and link it here.)*
