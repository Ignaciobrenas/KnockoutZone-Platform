# ðŸ¥Š Knockout Zone Â· Combat Sports Event & Fighter Management Platform

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Frontend-Responsive_CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/Academic-1Âº_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> ðŸŽ“ **Academic Project Notice:** Developed as an evaluative practical examination project for the **1st year of Web Application Development (DAW)** at **STUCOM Pelai** (Barcelona) within the Web Client & Server Development module (MP0487).

---

## ðŸ“Œ Overview / DescripciÃ³n General

### ðŸ‡¬ðŸ‡§ English
**Knockout Zone** is a full-stack web application dedicated to combat sports management (MMA, Boxing, Kickboxing, BJJ). It enables event promoters to publish fight cards, register fighters with their respective records and weight classes, and allows fans to discover upcoming matches, reserve tickets, and view event schedules.

### ðŸ‡ªðŸ‡¸ EspaÃ±ol
**Knockout Zone** es una plataforma web full-stack para la promociÃ³n y gestiÃ³n de deportes de contacto (MMA, Boxeo, Kickboxing, BJJ). Permite a promotores dar de alta eventos y veladas, gestionar fichas de luchadores con sus rÃ©cords y categorÃ­as de peso, y facilita a los aficionados descubrir combates y reservar entradas.

---

## âœ¨ Key Features

- ðŸ¥Š **Event & Fight Card Management:** Create, edit, and categorize combat events with dates, venues, and posters.
- ðŸ¥‹ **Fighter Profiles:** Track disciplines, records (W-L-D), weight classes, and bios.
- ðŸŽŸï¸ **Ticketing & Booking:** Seat reservation system for upcoming sports galas.
- ðŸ” **Role-Based Access Control (RBAC):** Distinct dashboards for administrators, promoters, and regular users.
- ðŸ“± **Modern Combat UI:** Dark theme aesthetic with responsive card grids and modals.

---

## ðŸ—ï¸ Architecture

- **EventController.php:** Handles event creation, scheduling, ticket allocation, and fight roster pairing.
- **UserController.php:** Manages user authentication, session security, and profile updates.
- **Database Layer:** Relational schema supporting many-to-many relationships between events and fighters.

---

## ðŸš€ How to Run

1. Place the project in your local web server directory (htdocs or www).
2. Import the database schema into MySQL.
3. Access http://localhost/KnockoutZone-Platform in your browser.

---

## ðŸ“„ License

Distributed under the **MIT License**.
