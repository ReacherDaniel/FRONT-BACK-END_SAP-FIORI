# SAP Fiori & SAP CDS – Front Back End Web Application

This repository contains a full-stack SAP application using **SAP Fiori (UI5)** for the frontend and **SAP CDS (Core Data Services)** for the backend, developed as an enterprise-style web solution.

The project was structured to demonstrate the integration of a SAP Fiori user interface with OData services exposed through SAP CDS, enabling modern CRUD operations and UI interactions in a business context.

---

## 🧩 Project Overview

This solution includes:
- **SAP Fiori (UI5)** frontend application
- **SAP CDS backend services** with OData endpoints
- Integration between frontend and backend using OData protocol

The application is designed to manage catalog or business-related data through an intuitive UI and structured backend logic.

---

## 🏗️ Architecture Summary

```text
SAP Fiori UI5 (Frontend)
        ↓
   OData Services
        ↓
     SAP CDS (Backend)
Frontend SAP Fiori components communicate with backend services via OData protocols, allowing flexible data retrieval, modification, and UI rendering.

Main Capabilities:

UI built with SAP Fiori UI5

Backend services using SAP CDS

OData service integration

CRUD operations

Modular project structure

BAT files for starting APIs and frontend

Project Structure:

The main folders and components include:

├── Front-SAP-Fiori-master             # SAP Fiori frontend
├── DAM_G5A_6PM_E1_SAP_CDS-main        # Backend CDS service project
├── Inversions_SAPCAP-main             # Additional backend module
├── INICIAR_API_ESTRATEGIA.bat         # Startup scripts
├── INICIAR_API_SECURITY.bat
├── INICIAR_FRONTEND.bat

Technologies Used

SAP Fiori UI5

SAP CDS (Core Data Services)

OData Services

JavaScript

CAP principles

Collaboration:

This repository was forked from another implementation and adapted with enhancements and integrations.

Original project (forked):

https://github.com/Yorsh2/FINAL-FRONT-BACK-END_SAP-FIORI

Purpose:

This project was developed to explore and apply full-stack SAP development using SAP Fiori UI5 and SAP CDS, demonstrating:

Enterprise-level UI with SAP Fiori

Backend data modeling and services using CDS

OData communication

Integration between frontend and backend SAP technologies

Notes:

To run this project, you will need an SAP development environment capable of running SAP Fiori and SAP CDS backend services (e.g., SAP Business Application Studio or local SAP environment).


