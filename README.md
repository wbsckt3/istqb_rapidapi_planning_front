front for rapid api:  https://rapidapi.com/jaalza/api/refactorii

API Overview

ISTQB-Based Test Automation Planning API with AI Plan your automated testing strategies with the power of Artificial Intelligence. This API leverages AI to generate optimized test plans based on ISTQB standards and user-provided data, accelerating your QA process with precision and intelligence. Ideal for QA engineers, developers, and testing teams aiming for smarter and faster automation planning.

Key Features:

🔬 AI-generated test automation plans based on ISTQB principles. ⚙️ Designed for QA engineers, testers, and DevOps teams. 
🚀 Rapid integration for agile environments. 
✅ Google Sign-In authentication 
🏢 Multi-tenant company management 
👥 User–company relationships with assignable roles 
🧠 ISTQB-style end-to-end test planning 
📑 Support for preconditions, test data, steps, acceptance criteria, expected results, and more 
📊 Optimized for modern test frameworks like Cypress + Cucumber 
🔐 Secure, structured, and standards-compliant 
🌐 Test environments, priorities, pipelines, and traceability included

AI-powered ISTQB Test Planning – smart automation strategies.

ISTQB-Based Test Automation Planning API

This API provides a structured and professional approach to planning functional automated tests, aligned with ISTQB best practices. It's ideal for QA engineers, test automation developers, and team leads who need to organize, document, and execute test plans across multiple companies and user environments.
🚀 Key Features:

✅ Google Sign-In authentication

🏢 Multi-tenant company management

👥 User–company relationships with assignable roles

🧠 ISTQB-style end-to-end test planning

📑 Support for preconditions, test data, steps, acceptance criteria, expected results, and more

📊 Optimized for modern test frameworks like Cypress + Cucumber

🔐 Secure, structured, and standards-compliant

🌐 Test environments, priorities, pipelines, and traceability included

📘 Ideal Use Cases: QA teams planning automation in a structured, standards-based way

SaaS platforms managing tests for multiple client companies

QA consultants offering certified test planning services

🧭 Available Endpoints:

Endpoint Description

1. POST /auth/google-signin

Authenticate a user via Google

2. POST /companies

Register a new company and associate it with the user

3. POST /companies/relate-user

Relate an authenticated user to a company

4. GET /companies

Retrieve companies associated with the user

5. POST /workflow/planeador_de_automatizacion_ISTQB

Create a test plan following ISTQB structure

6. GET /workflow/planeador_de_automatizacion_ISTQB/getExercisesInTestAutomationPlanById

List user's ISTQB-style test plans  

7. GET /workflow/planeador_de_automatizacion_ISTQB/verifyExercisesInPath

Retrieve a specific test plan by ID

🛠 Tech & Best Practices:

Node.js, Express

MongoDB (multi-tenant schema)

UUIDs for secure and unique identification

Clear separation of concerns between users, companies, and test flows

Follows the full test lifecycle as recommended by ISTQB

