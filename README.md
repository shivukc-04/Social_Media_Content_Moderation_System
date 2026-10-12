# Social Media Content Moderation System

A full-stack social media and content moderation platform built with **Java 21**, comprising a **Spring Boot REST API** backend and a **JavaFX desktop client**.

---

## Key Features

* **Role-Based Access Control:** Secure JWT authentication supporting `USER`, `MODERATOR`, and `ADMIN` roles.
* **Social Feed & Interactions:** Create posts, add comments, like/dislike, and report inappropriate content.
* **Moderation Workflow:** Dedicated queues for reviewers to manage flagged posts, track moderation logs, and process user appeals.
* **Administrative Oversight:** Comprehensive system management, user controls, and moderation overview.

---

## Tech Stack

* **Backend:** Java 21, Spring Boot 3.3.1, Spring Security, Spring Data JPA, Hibernate, H2 / PostgreSQL.
* **Frontend:** JavaFX 21, FXML, CSS, Gson, custom HTTP REST client.

---

## Getting Started

### 1. Run the Backend
Navigate to the project root and start the Spring Boot API:
```bash
mvn spring-boot:run
