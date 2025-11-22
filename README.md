# Fullstack-Business-Application-Using-ABAP-RAP-And-FIORI
SAP BTP ABAP Environment

# ABAP RAP & Fiori Fullstack Application

This repository contains a **Fullstack Application** built using **ABAP RAP (Restful ABAP Programming)** for the backend and **SAP Fiori** for the frontend. The project showcases the ability to create and deploy end-to-end solutions in SAP environments utilizing RAP framework for the business logic and OData services along with a custom Fiori application for the user interface.

---

## Project Overview

This project is designed to demonstrate the following:
- Creation of backend services using SAP's **ABAP RESTful Application Programming Model** (ABAP RAP). 
- Integration of Fiori UI components to consume OData services provided by the ABAP backend.
- Repository structure for staging an SAP Fullstack Application on GitHub for version control and collaboration.

---

## Features
1. ABAP RAP Backend:
   - **CDS Views** for data modeling: `ZRAP100_CDS_VIEWNAME`.
   - **Service Definitions** to expose OData services using Entity and Action interfaces: `ZRAP100_SRVDEF`.
   - **Service Bindings** configuration: `ZRAP100_UI_TRAVEL_O4_200`.
   - Custom **business logic layers** implemented with ABAP classes: `ZRAP100_CL_LOGIC`.

2. Fiori Frontend:
   - XML views and controllers for modern user interfaces.
   - **manifest.json** for application configuration.
   - **Component.js** and modular JavaScript files for responsive interaction.
   - Localization files (i18n.properties) for multi-language support.
   - Custom theming with CSS and additional assets (images, logos).

---

## Project Structure
The repository is structured as follows:

---

## Prerequisites

Before deploying this project, ensure the following prerequisites are met:
1. Access to an **SAP environment** with ABAP Development Tools (ADT) in Eclipse.
2. Access to SAP Gateway or Front-End Server for hosting the Fiori application.
3. Basic understanding of:
   - ABAP RAP concepts, including CDS views, Services, and OData.
   - Fiori basics, including XML views, controllers, and deployment.
4. Git must be installed locally to clone and manage this repository.

---

## Installation Steps

Follow these steps to deploy the ABAP RAP and Fiori application in your environment:

### Backend (ABAP RAP)
1. **Clone Repository:**
   ```bash
   git clone https://github.com/Rushibagul-20/Fullstack-Business-Application-Using-ABAP-RAP-And-FIORI.git
