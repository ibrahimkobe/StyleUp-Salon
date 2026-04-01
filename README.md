# ✂️ StyleUp - Digital Salon Management System

![Adalo](https://img.shields.io/badge/Built%20With-Adalo-FF6B6B?style=for-the-badge&logo=adalo)
![Lifecycle](https://img.shields.io/badge/SDLC-Agile-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-MVP%20Completed-success?style=for-the-badge)

StyleUp is a modern, data-driven salon management application designed to digitize customer bookings, streamline stylist schedules, and provide business owners with a clear operational dashboard. Built as a Capstone project, it focuses on high-quality user experience and efficient appointment logic.

## 🚀 Live Demo
**[Experience the Live App Here](https://previewer.adalo.com/9133db7d-b1b9-43dd-90db-7a6292079ea2?target=818468a1bfad492599706dafa106d579&params=%7B%7D)**

### App Previews
<p align="center">
  <img src="[Welcome.png]" width="200" alt="Welcome Screen">
  <img src="[Login.png]" width="200" alt="Login Page">
  <img src="[Profile.png]" width="200" alt="Profiles & Admin Dashboard">
  <img src="[Service.png]" width="200" alt="Services">
</p>

---

## ✨ Key Features

### For Clients
* **Frictionless Booking:** A streamlined 3-step booking flow (Service → Stylist → Time).
* **Service Catalog:** Real-time visibility into available services and pricing.
* **Personalized History:** Secure access to past and upcoming appointment records.

### For Stylists
* **Schedule Management:** Dedicated mobile views for stylists to check their daily assigned appointments.
* **Availability Toggles:** Ability to block out time for breaks or unavailability.

### For Admins / Salon Owners
* **Decision Support Dashboard:** A protected overview of all shop bookings and stylist performance.
* **Staff & Service Management:** Easily update service prices or add new stylists to the team.

---

## 🛠️ Technical Architecture

This application was developed utilizing an **Agile Software Development Lifecycle (SDLC)**, prioritizing rapid prototyping and user feedback.

* **Frontend & Backend Engine:** Adalo (No-Code Platform)
* **Database:** Relational Database model handling One-to-Many and One-to-One relationships across Users, Services, and Appointments.
* **Data Flow:** Structured using strict Context and Level 0 Data Flow Diagrams (DFDs) to ensure zero data-leakage between client views and admin privileges.

### Core Logic Highlight: The Booking Engine
The booking engine utilizes a sequence of conditional checks to prevent double-booking. The app passes relational data (`Current Service` + `Current Stylist`) through the navigation flow, ensuring precise data integrity before writing to the Appointment database.

---

## 📂 Documentation

As part of the software engineering process, comprehensive documentation was generated for this system:
1. **Feasibility Study:** Economic, Technical, and Operational viability analysis.
2. **Software Requirements Specification (SRS):** Detailed functional and non-functional requirements.
3. **Requirements Traceability Matrix (RTM):** Mapping test cases to initial requirements.
4. **System Design Specification (SDS):** Featuring ERDs, Flowcharts, and Extended Finite State Machines (EFSM).

*(Note: Full documentation is available upon request).*

---

## 👨‍💻 Author

**Ibrahim Abu Kobe**
* Software Engineering Student at Al Hussein Technical University (HTU)
* GitHub: [@YourGitHubUsername](https://github.com/ibrahimkobe)
* LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/ibrahim-abukobe/)
