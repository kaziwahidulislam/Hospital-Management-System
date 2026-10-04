# 🏥 Hospital Management System (HMS)

> **A modern, modular Node.js & Express backend for seamless healthcare management and clinical workflows.** 🩺✨

---

---

## 💡 Overview

Managing a hospital involves complex role permissions, scheduling, and diagnostic tracking. **Hospital Management System** provides a lightweight, scalable backend framework tailored for handling multi-role operations.

Whether you are an **Admin** overseeing hospital modules, a **Doctor** reviewing appointments, or a **Patient** checking lab results, this system routes and validates every request securely through custom middleware architecture.

```text
               +----------------------------------+
               |    Hospital Management System     |
               +----------------------------------+
                                |
        +-----------------------+-----------------------+
        |                       |                       |
  🛡️ Admin Panel          👨‍⚕️ Doctor Portal         🩺 Patient Portal
  - System Config          - Consultations          - Appointments
  - Role Access            - Patient Records        - Lab Reports

```

---

## 📸 Interface Preview

| 🚨 Doctor & Admin Portal | 📊 Patient & Lab Workflow |
| --- | --- |
| <img src="[https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWVndmU3OHJycWVtbTB1bzlyeG44ZnA3dWJyaWZnbHNzcTNpdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw](https://www.google.com/search?q=https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWVndmU3OHJycWVtbTB1bzlyeG44ZnA3dWJyaWZnbHNzcTNpdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw) | L1JBS3BqTGxHOUVGei9naWY/giphy.gif" width="400" alt="Doctor Portal Demo"> |

---

## 🔥 Key Features

* **🔐 Multi-Role Authentication**: Middleware-backed access layers for Admins, Doctors, and Patients.


* **📅 Appointment Engine**: Real-time management of doctor schedules and patient bookings.


* **🧪 Lab Testing Pipeline**: Integrated system to record, track, and report diagnostic laboratory tests.


* **🛠️ Modular Express Design**: Dynamic templating via EJS/Handlebars paired with clean routing logic.



---

## 🛠️ Tech Stack & Dependencies

| Category | Technologies / Libraries |
| --- | --- |
| **Core Runtime** | `Node.js` 🟢

 |
| **Framework** | `Express.js` 🚀

 |
| **Views / Templates** | `EJS`, `Handlebars` 🎨

 |
| **Mock Data & Dev** | `Faker.js` 🎲, `Nodemon` 🔄, `Marked` 📝

 |

---

## 📂 Project Structure

```text
Hospital_Management_System/
├── 📄 app.js               # Main application entry point[cite: 1]
├── 📄 database.txt         # Schema definitions & seed configurations[cite: 1]
├── 📁 middleware/          # Role authentication & route validation[cite: 1]
│   ├── 🛡️ AdminLogin.js   # Admin access middleware[cite: 1]
│   ├── 📅 Appointment.js  # Booking & schedule handler[cite: 1]
│   ├── 🩺 Doctor.js       # Doctor portal logic[cite: 1]
│   ├── 🔐 DoctorLogin.js  # Doctor auth handler[cite: 1]
│   ├── 🧪 LabTest.js      # Diagnostic test operations[cite: 1]
│   └── 👤 Patient.js      # Patient route handler[cite: 1]
└── 📄 package.json         # Dependencies & scripts[cite: 1]

```

---

## 🚀 Quick Start Guide

### 1️⃣ Prerequisites

Make sure you have **Node.js** (v14+ recommended) and **npm** installed on your machine.

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Hospital_Management_System_project.git
cd Hospital_Management_System_project

```

### 3️⃣ Install Dependencies

```bash
npm install

```

### 4️⃣ Run the Server

```bash
# Start in development mode with Nodemon
npm run dev

# Start in production mode
node app.js

```

The application will launch on `http://localhost:3000` (or your configured port).

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

⭐ **If you found this project helpful, give it a star!** ⭐