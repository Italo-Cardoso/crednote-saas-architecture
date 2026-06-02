# CredNote — B2B Financial Automation & Debt Recovery SaaS

CredNote is a robust, production-ready B2B Software-as-a-Service (SaaS) platform engineered to solve a critical retail market pain point: merchant delinquency. The platform automates complex financial notification and collection workflows, leveraging real-time messaging and modern fintech integrations to reduce payment delays instantly.

## 🚀 Architectural Overview

The system is built on top of a fully decoupled **MERN Stack** coupled with **TypeScript** to guarantee strict typing, high availability, scalability, and fast data transaction processing.

### Key Features & Technical Implementations

*   **Automated Messaging Engine:** Implemented the `Baileys` library to establish a resilient, background-running WhatsApp messaging worker that dynamically dispatches collection alerts based on real-time triggers.
*   **Fintech Gateway Integration:** Deeply integrated with the `Asaas` payment gateway API to handle dynamic Pix generation, webhook listeners for real-time payment confirmation, and automated customer status updates.
*   **Responsive Analytical Dashboard:** Developed a secure, single-page application (SPA) dashboard using React to provide merchants with interactive metric charts, outstanding debt tracking, and customer management controls.
*   **Production Cloud Infrastructure:** Configured automated CI/CD deployment pipelines utilizing `Vercel` for the frontend client hosting and `Render` for the backend Node.js microservice layer.

## 🛠️ Tech Stack & Ecosystem

*   **Backend:** Node.js, Express.js, RESTful APIs, Baileys Library (WhatsApp API Automation).
*   **Frontend:** React, HTML5, CSS3, Tailwind CSS.
*   **Database:** MongoDB (Mongoose ODM).
*   **Integrations:** Asaas Payment Gateway (Pix & Automated Webhooks).
*   **DevOps:** Vercel, Render, Git.

---
*Note: This repository serves as a public architectural case study. The core business logic and source code are kept private to protect commercial intellectual property.*
