# Expense Tracker 🛍️ – Mobile Application with Microservices Architecture

Developed a comprehensive Expense Tracker application for efficient financial management, incorporating user authentication, manual and automated expense tracking, and delivering personalized financial tips and alerts.

## Features

- Implemented **Kong API Gateway** and **Eureka Server** to access and manage different services.
- Added features like **user authentication**, **manual expense management**, and **automated expense tracking through SMS parsing functionality using Large Learning model (LLM)** like Mistral AI.
- Designed a **fault-tolerant** and **scalable** system ensuring high availability and low latency for optimal user experience using **Resilience4J Circuit Breaker**.
- Additionally enabled system to **analyze user financial behavior**, **provide personalized tips for improvement** as well as **send notifications to alert users about financial risks and overspending**
- Used **Grafana** Stack for observability as well as documented using **Swagger UI**.

## Tech Stack

React-Native, Spring Boot, Flask, LLM (Mistral AI), MySQL, Kafka, Docker, Grafana

## All Microservices Link

- [Authentication Service](https://github.com/chandankrr/auth-service)
- [User Service](https://github.com/chandankrr/user-service)
- [Data Science Service](https://github.com/chandankrr/data-science-service)
- [Expense Service](https://github.com/chandankrr/expense-service)

## Data Flow Diagram

![diagram-export-5-18-2024-10_47_52-PM](https://github.com/chandankrr/expense-tracker/assets/87066174/98323035-a21f-4dec-b009-bf22e9093868)
