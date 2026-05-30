# 🔍 Knockout Zone · Codebase QA, Auditing & Bug-Fixing Assignment

<p align="center">
  <img src="https://img.shields.io/badge/Role-QA_%26_Bug_Fixing-FF5722?style=for-the-badge" alt="QA Role" />
  <img src="https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Workflow-Pull_Requests-047857?style=for-the-badge&logo=github&logoColor=white" alt="PRs" />
  <img src="https://img.shields.io/badge/Academic-1º_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> ⚠️ **Academic Context & Project Attribution Notice:**
> The base web application (*Knockout Zone - Combat Sports Management Platform*) was provided as an **evaluative testing and codebase auditing exam** for the **1st year of Web Application Development (DAW)** at **STUCOM Pelai** (Barcelona) within module MP0487.
> 
> My contribution to this repository consisted of **analyzing a third-party codebase, diagnosing intentional defects/issues, reproducing bugs, refactoring vulnerable/broken code, and submitting pull request resolutions**.

---

## 📌 Overview / Descripción General

### 🇬🇧 English
This repository documents a practical software quality assurance (QA) and debugging assignment. Given a pre-existing full-stack PHP web application for combat sports management, the objective was to:
1. Audit the source code and reproduce reported defects.
2. Identify root causes in permission logic, templates, and controllers.
3. Implement clean, robust fixes following best security practices.
4. Submit documented bug fixes via Git feature branches and Pull Requests.

### 🇪🇸 Español
Este repositorio recoge una práctica evaluativa de aseguramiento de calidad (QA), auditoría de código y corrección de errores sobre una aplicación web PHP preexistente para gestión de veladas de deportes de contacto. El objetivo consistió en auditar la base de código, reproducir incidencias reportadas, reparar los fallos en controladores y vistas, y documentar la solución mediante ramas de Git y Pull Requests.

---

## 🛠️ Resolved Issues & Pull Requests

### 🐛 Issue #1 / Pull Request #2:
- **Title:** `edit/delete buttons not visible for admin in events list`
- **Defect Diagnosis:** In the event listing view, administrative action buttons (`Edit`, `Delete`) failed to render due to an incorrect session role comparison and template condition flaw.
- **Resolution:** Refactored user session role verification in the view templates and controller middleware, ensuring authorized administrators have full management controls while maintaining restricted views for standard users.
- **Validation:** Verified across multiple user session states (guest, logged-in user, and platform administrator).

---

## 📄 License

Distributed under the **MIT License**.
