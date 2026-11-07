# Ebin Antony Elenjikkal — Professional Civil Engineering Portfolio

> **"Building Beyond Drawings – Connecting Engineering Knowledge, Construction Execution and Digital Innovation."**

A world-class, premium, modern, fully responsive personal portfolio website for **Ebin Antony Elenjikkal**, final-year B.Tech Civil Engineering student at **TKM College of Engineering, Kollam**, with Site Engineer experience at **L&T Construction** (Cochin New Dry Dock Project, ₹1,500 Crore).

---

## 🏗️ Highlights & Architecture

- **Zero-Dependency & Fast**: Runs immediately in any browser without needing `npm install` or complex build toolchains. Double-click `index.html` to open locally.
- **Design Aesthetic**: Minimalist, high-end architectural blueprint aesthetic combining **Deep Marine Navy** (`#0B132B`), **Crisp White / Technical Light Grey**, and **Construction Safety Orange** (`#EA580C` / `#FF7722`).
- **Typography**: Precision architectural pairing with Google Fonts (`Manrope` for bold structural headers, `Inter` for technical data, `JetBrains Mono` for coordinates & formulas).
- **Dark & Light Mode**: Seamless theme toggle with local storage persistence and system preference autodetection.
- **Interactive BBS Calculator**: Live Bar Bending Schedule (BBS) rebar weight calculator simulating IS 2502 / BS 8666 standards ($Unit\ Weight = \frac{d^2}{162.28}\ kg/m$) with real site presets from the L&T Dry Dock project.
- **BIM Digital Twin Explorer**: Interactive facility management telemetry simulator modeled after the TKMCE Library Building Services (AHU HVAC, Substation, Fire Suppression, Structural Health).
- **Expandable Project Modals**: Deep-dive interactive case studies with tabs for *Executive Summary*, *Engineering Methodology*, and *Key Deliverables & Value*.
- **Award Verification Modals**: Detailed modals for all 5 major competition laurels (1st Prize Revit Tharangam 2025 AISAT, 1st Prize Auto Clash CET, Runner-up BAI EMERGE 2026, 2nd Prize CAD War RIT, 2nd Prize Draft & Craft NIT Calicut).
- **Printable ATS Resume Modal**: Built-in, high-contrast, ATS-compliant curriculum vitae with one-click print/PDF export.
- **Functional Contact Form & Copy-to-Clipboard**: Real-time form validation with simulated sending state and one-click copy buttons for email and phone with toast notifications.
- **Responsive Navigation**: Fixed glassmorphic navigation header with scroll progress bar, scroll spy link highlights, and mobile slide-in drawer.

---

## 📁 Project Structure

```
ebin-portfolio/
│
├── index.html              # Master Semantic HTML5 Portfolio (All 9 sections + Modals)
├── css/
│   └── style.css           # Comprehensive CSS3 architecture (Tokens, Light/Dark, Glassmorphism, Print)
├── js/
│   └── main.js             # Modular JS (Theme, BBS calculator, BIM telemetry, Modals, Form validation)
└── README.md               # Documentation & Deployment Guide
```

---

## 🚀 How to Run Locally

1. Simply double-click `index.html` (or right-click → **Open with Chrome / Edge / Firefox / Safari**).
2. No Node.js, Python, or build steps required.

---

## ✏️ Customization & Personal Placeholders

To personalize your details prior to publishing:

1. **Email & Phone**:
   - Open `index.html` and search for `ebinantony@example.com` and `+91 98765 43210` to update them with your active contact details.
2. **LinkedIn URL**:
   - Update `https://www.linkedin.com/in/ebin-antony-elenjikkal/` with your exact profile slug.
3. **Profile Photo**:
   - In `index.html`, inside `.profile-image-box`, you can replace the `.engineer-avatar-graphic` with your actual portrait photo:
     ```html
     <img src="assets/profile.jpg" alt="Ebin Antony Elenjikkal" style="width:100%; height:100%; object-fit:cover; border-radius:20px;" />
     ```
4. **Physical Resume File**:
   - If you have an existing PDF resume, place it as `resume.pdf` in the `ebin-portfolio/` folder and link any download button to `href="resume.pdf" download`.

---

## 🌐 Free Static Deployment

### Option 1: GitHub Pages
1. Push this folder to a GitHub repository (e.g. `ebin-antony-portfolio`).
2. Go to **Settings** → **Pages**.
3. Under **Branch**, select `main` and root `/`, then click **Save**.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

### Option 2: Netlify
1. Drag and drop the `ebin-portfolio` folder directly into [app.netlify.com/drop](https://app.netlify.com/drop).
2. Netlify instantly deploys it with a free SSL certificate.

### Option 3: Vercel
1. Run `npx vercel` or connect your GitHub repository in the Vercel dashboard.

---

## 🏆 Summary of Portfolio Sections

| # | Section | Key Contents |
|---|---|---|
| **01** | **Hero & Highlights** | Personal branding statement, CAD coordinates, profile presentation, animated stats strip. |
| **02** | **About Me** | Journey from Diploma (8.74 CGPA) to B.Tech Civil Engineering at TKMCE; 4 core engineering pillars. |
| **03** | **L&T Experience** | Cochin New Dry Dock Project (₹1,500 Cr), North Section execution, BBS calculations, ₹50-80L monthly billing. Includes **Live BBS Calculator**. |
| **04** | **Projects** | BIM Digital Twin Framework (TKMCE Library), QS & Subcontractor Billing, Multi-Storey Structural Design (ETABS), Site Internships. Includes **BIM Telemetry Explorer**. |
| **05** | **Technical Skills** | 6 categorized discipline cards: QS, BIM, Structural Design, Project Planning, Surveying, and Professional Competencies. |
| **06** | **Achievements** | 1st Prize Revit (AISAT), 1st Prize Auto Clash (CET), Runner-up BAI EMERGE 2026, 2nd Prize CAD War (RIT), 2nd Prize NIT Calicut. |
| **07** | **Education & Certs** | B.Tech Civil Engineering (TKMCE Kollam), Diploma in Civil Engineering (8.74 CGPA), BIMLABS Revit, ETABS, BBS training. |
| **08** | **Beyond Engineering** | Campus leadership, MUN debate, fitness/marathon endurance, sustainable Construction 4.0. |
| **09** | **Contact & Connect** | Direct message form with validation, copy-to-clipboard contact channels, ATS resume view & print. |

