<div align="center">

# 🏥 Care Heaven
### Modern Dental Clinic & Comprehensive Healthcare Platform

[![React](https://img.shields.io/badge/React-18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <strong>Care Heaven</strong> is a dental clinic and healthcare web application engineered to deliver an intuitive patient experience. Featuring modern UI/UX design, treatment showcases, interactive online appointment scheduling with instant confirmation, an integrated admin management dashboard, and multichannel communication support.
</p>

</div>

---

## 📑 Table of Contents

- [✨ Key Features](#-key-features)
- [📞 Contact Information (Primary & Alternative)](#-contact-information)
- [🛠️ Tech Stack](#️-tech-stack)
- [💻 Pages & Modules](#-pages--modules)
- [🚀 Quick Start & Local Preview](#-quick-start--local-preview)
- [📂 Project Structure](#-project-structure)
- [🛡️ Security & Privacy](#️-security--privacy)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Key Features

- **💎 Modern Aesthetic Design:** Built with clean typography, cohesive medical color palettes (emerald, cyan, and deep navy), micro-animations, and fluid transitions.
- **📱 100% Responsive & Accessible:** Optimized layout providing an effortless experience across mobile phones, tablets, and high-resolution desktops.
- **🦷 Comprehensive Dental Services Showcase:** Interactive catalog presenting specialized treatments including cosmetic smile design, root canal therapy, implant restorations, teeth whitening, and preventive hygiene.
- **📅 Interactive Appointment Booking (`/book-appointment`):**
  - Real-time client-side form validation (name, phone, email, date, time slot, treatment).
  - Flexible time slot selection (morning and afternoon clinic hours).
  - Immediate request status and animated confirmation screen.
- **📊 Embedded Admin Management Dashboard (`/admin-dashboard`):**
  - KPI summary metrics (Total, Pending, Confirmed, Cancelled).
  - Live search filter by patient name, treatment type, or booking date.
  - Status filter tabs (All, Pending, Confirmed, Cancelled).
  - One-click actions to confirm or cancel patient requests with persistent `localStorage` synchronization.
- **📲 Direct Communication Channels:** One-tap calling, direct WhatsApp chat integration, and mailto triggers.

---

## 📞 Contact Information

Care Heaven offers multiple communication channels for inquiries, patient consultations, and emergency dental support:

| Channel | Primary Details | Alternative / Secondary Details |
| :--- | :--- | :--- |
| 📞 **Telephone** | **Main Line:** `+1 (555) 123-4567` | **Alt Line:** `+1 (555) 987-6543` |
| 💬 **WhatsApp** | `+1 (555) 987-6543` | [Chat on WhatsApp](https://wa.me/15559876543) |
| ✉️ **Email** | **General & Booking:** `contact@careheaven.demo` | **Support & Emergencies:** `support@careheaven.demo` |
| 📍 **Clinic Address** | Care Heaven Clinic, 123 Healthcare Blvd, Suite 400, Medical District, City 12345 | Accessible via Medical District transit hub & on-site parking |
| 🕒 **Operating Hours** | **Monday – Saturday:** 9:00 AM – 7:00 PM | **Sunday:** Closed (Emergency on-call available) |

---

## 🛠️ Tech Stack

- **Framework / Core:** [React 18](https://react.dev/) with SPA routing
- **Build Tool:** [Vite](https://vitejs.dev/) for bundling and asset optimization
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) with custom medical-grade theme tokens
- **Icons:** [Lucide React](https://lucide.dev/) for crisp, scalable vector icons
- **Animations:** [Framer Motion](https://www.framer.com/motion/) for micro-interactions and scroll-triggered reveals
- **Data Persistence:** Browser `localStorage` for appointment simulation and status management

---

## 💻 Pages & Modules

### 1. Landing Page (`/`)
- **Navigation Bar:** Fixed header featuring the **Care Heaven** brand logo, smooth navigation anchors (Services, About, Tour, Reviews, Contact), and a high-visibility *Book Appointment* CTA.
- **Hero Section:** Engaging headline, trust badges (12+ Years Experience, 5,000+ Satisfied Patients), and quick booking shortcuts.
- **Services Catalog:** Grid breakdown of key procedures with clear descriptions.
- **Doctor & Clinic Profile:** Qualifications (BDS, MDS Endodontics, Certified Implantologist), clinical experience, and clinical approach.
- **Clinic Tour:** High-resolution gallery showcasing reception, modern operatories, and sterilization equipment.
- **Patient Reviews:** Genuine patient testimonials with 5-star rating visual badges.
- **Direct Contact Box:** Complete clinic coordinates with phone numbers, emails, WhatsApp link, and embedded map placeholder.

### 2. Appointment Booking Engine (`/book-appointment`)
- Comprehensive booking questionnaire collecting patient details and treatment preferences.
- Automated validation guarding against incomplete submissions or invalid contact formatting.
- Instant feedback modal with option to navigate to the live demo dashboard.

### 3. Demo Admin Dashboard (`/admin-dashboard`)
- Management portal simulating a real dental office reception desk.
- Real-time metric cards updating dynamically with status changes.
- Responsive table with patient details, requested appointment time, and quick status toggle buttons.

---

## 🚀 Quick Start & Local Preview

Modern web browsers enforce CORS security policies that block JavaScript ES Modules (`<script type="module">`) when opened directly via the `file://` protocol (double-clicking `index.html`). To view the website smoothly, run a local development/preview server:

### Option 1: Using npm (Recommended)
```bash
# In the project directory:
npm run dev
```

### Option 2: Using npx serve or Python
```bash
# Using npx
npx serve .

# Or using Python 3
python -m http.server 3000
```
Then open `http://localhost:3000` (or the port shown in your terminal) in your browser.


---

## 📂 Project Structure

```text
Care-Heaven/
├── assets/
│   ├── index-C23ITIrd.js    # Production application bundle (React + Routing + Components)
│   └── index-DxSexJfH.css   # Compiled Tailwind CSS design system styles
├── index.html               # Main HTML entry with SEO meta tags & Care Heaven branding
├── CONTRIBUTING.md          # Community contribution guidelines
├── SECURITY.md              # Security policy and vulnerability disclosure procedures
├── LICENSE                  # Project open-source license
└── README.md                # Comprehensive project documentation
```

---

## 🛡️ Security & Privacy

We treat user privacy and data security seriously. For information on reporting vulnerabilities, please consult our [Security Policy](SECURITY.md).

---

## 🤝 Contributing

Contributions, feedback, and feature suggestions are welcome! Please review our [Contributing Guidelines](CONTRIBUTING.md) to get started.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<div align="center">
  <br/>
  <sub>Care Heaven Dental Clinic • Dedicated to healthy, confident smiles</sub>
</div>
