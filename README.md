# UPPMS — University Programming Project Management System

> A full-stack university project management platform built with Laravel, React, and MySQL. UPPMS provides project lifecycle management, multi-tenancy, role-based access control, GitHub integration, XML-based registration, AI-assisted project development, academic tracking, and genetic algorithm-based scheduling.



\## 📌 Overview



\*\*UPPMS (University Programming Project Management System)\*\* is a full-stack web application designed to help universities manage the complete lifecycle of student programming projects.



The system brings together students, supervisors, committees, administrators, and university management in one platform, while providing tools for project management, academic tracking, scheduling, GitHub integration, XML-based registration, and AI-assisted project development.



The project was developed as a \*\*graduation project\*\* with a strong focus on backend architecture, business logic, APIs, database design, and complex scheduling algorithms.



\---



\## 🚀 Main Features



\### 🏢 Multi-Tenant Architecture



The system supports multiple universities within the same application while keeping university-specific data isolated.



\* Tenant-aware data management

\* University-level configuration

\* Tenant-scoped database queries

\* Centralized Super Admin management



\### 🔐 Role-Based Access Control



Different users receive different permissions based on their roles.



Examples include:



\* Super Admin

\* University Admin

\* Supervisor

\* Student

\* Committee Member



The system uses role and permission management to control access to resources and operations.



\### 📄 XML Registration \& Import



University users can register and import data using XML files.



The system provides:



\* XML validation

\* User registration/import

\* Import logs

\* Error handling

\* Structured data processing



\### 📊 Academic Tracks \& Student Progress



The platform supports academic tracks and helps manage student progress throughout their project journey.



Features include:



\* Academic track management

\* Student progress tracking

\* Track requirements

\* Project-related academic data



\### 📁 Project Management



UPPMS manages the complete project workflow, including:



\* Project proposals

\* Project approval

\* Project versions

\* Tasks

\* Comments

\* Ratings

\* Notifications

\* Project activities



\### 🤖 AI Project Ideation



The system includes an AI-assisted ideation feature that can help students generate and explore project ideas.



The AI functionality supports:



\* Project idea generation

\* Idea recommendations

\* Structured project descriptions

\* Ideation request tracking



\### 🤖 AI Task Breakdown



Projects can be broken down into structured tasks using AI assistance.



The system tracks:



\* Task generation requests

\* Generated tasks

\* Task relationships

\* AI generation logs



\### 🧬 Genetic Algorithm Scheduling



One of the core technical components is a scheduling system based on a \*\*Genetic Algorithm\*\*.



It is designed to solve complex allocation and scheduling problems involving:



\* Defense sessions

\* Committees

\* Rooms

\* Time slots

\* Student projects

\* Scheduling constraints



The scheduling engine includes components such as:



\* Chromosomes

\* Genes

\* Population management

\* Fitness calculation

\* Evolutionary operators

\* Constraint violations

\* Schedule candidates



\### 🐙 GitHub Integration



The platform integrates with GitHub to connect student projects with their repositories.



The system supports functionality related to:



\* GitHub authentication

\* Repository linking

\* Git commits

\* Project versions

\* Repository activity



\### 📋 Activity Logging



Important system activities are tracked for auditing and monitoring purposes.



Examples include:



\* Project activities

\* User actions

\* XML import operations

\* AI operations

\* GitHub-related activities



\---



\## 🏗️ Architecture



The project follows a full-stack architecture consisting of a Laravel backend and React frontend.



```text

UPPMS

│

├── Backend

│   ├── Laravel

│   ├── PHP

│   ├── REST APIs

│   ├── MySQL

│   ├── Authentication \& Authorization

│   ├── AI Services

│   ├── GitHub Integration

│   ├── XML Processing

│   └── Genetic Algorithm Scheduler

│

└── Frontend

&#x20;   ├── React

&#x20;   ├── Vite

&#x20;   ├── JavaScript

&#x20;   └── REST API Integration

```



\---



\## 🛠️ Technologies



\### Backend



\* PHP

\* Laravel

\* RESTful APIs

\* MySQL

\* Eloquent ORM

\* Authentication \& Authorization

\* PHPUnit



\### Frontend



\* React

\* Vite

\* JavaScript

\* HTML

\* CSS



\### Integrations \& Other Technologies



\* GitHub API

\* XML

\* AI Services

\* Genetic Algorithms

\* REST APIs



\---



\## 📂 Project Structure



```text

UPPMS-Project/

│

├── backend last/

│   ├── app/

│   ├── database/

│   ├── routes/

│   ├── tests/

│   ├── config/

│   └── ...

│

├── frontend/

│   ├── src/

│   ├── public/

│   └── ...

│

├── .gitignore

├── SETUP.md

└── README.md

```



\---



\## 🧪 Testing



The backend contains automated tests covering important parts of the system, including:



\* AI ideation

\* AI task generation

\* Scheduling

\* XML import

\* XML registration

\* Academic tracks

\* Committees

\* Project proposals



Testing is implemented using Laravel/PHP testing tools.



\---



\## 🔑 Backend Highlights



The backend contains several dedicated services and components for complex business logic.



Examples include:



```text

AIIdeationService

AITaskService

GeneticSchedulerService

GitHubService

XmlImportService

```



The scheduling module is separated into dedicated components for:



```text

Chromosome

Gene

FitnessCalculator

PopulationManager

EvolutionaryOperators

ScheduleCandidate

SchedulingContext

SchedulingResult

Violation

```



This separation helps keep complex business logic modular and maintainable.



\---



\## 🎓 Graduation Project



UPPMS was developed as a university graduation project with the goal of addressing real-world challenges in managing programming projects within academic environments.



The project combines:



\* Backend engineering

\* Database design

\* REST API development

\* Authentication \& authorization

\* Multi-tenancy

\* Algorithmic problem solving

\* AI integration

\* Third-party API integration

\* Automated testing



\---



\## 👨‍💻 My Contribution



My primary contribution to this project was focused on \*\*Backend Development\*\*, including work related to:



\* Laravel backend development

\* REST API development

\* Database and business logic

\* Role-Based Access Control

\* Multi-Tenant Architecture

\* XML registration and import

\* Activity logging

\* GitHub integration

\* Academic tracks

\* AI-assisted project recommendations

\* AI task breakdown

\* Genetic Algorithm scheduling

\* Backend testing



This repository represents the project as a team-developed system, while highlighting my primary technical focus on backend engineering.



\---



\## ⚙️ Setup



For installation and local development instructions, see:



\*\*\[SETUP.md](SETUP.md)\*\*



Before running the project locally, make sure the required environment variables, database configuration, backend dependencies, and frontend dependencies are configured.



> Never commit `.env` files or API credentials to the repository.



\---



\## 📌 Project Status



This repository contains the graduation project implementation and is maintained as part of my software engineering portfolio.



Future improvements may include:



\* Improved deployment configuration

\* CI/CD automation

\* Additional automated tests

\* API documentation

\* Performance improvements

\* Enhanced monitoring and logging

\* Additional AI capabilities



\---



\## 📄 License



This project was developed as an academic graduation project.



Unless otherwise specified, the code in this repository should be considered for educational and portfolio purposes.



