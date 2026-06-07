# Eduford-College-Website

# 🎓 Eduford University — College Website

A fully responsive, multi-page college website built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks, no libraries, no backend required. Designed to be hosted on **GitHub Pages** instantly.

---

## 🌐 Live Demo


> **[ https://neeraj-4425.github.io/Eduford-College-Website/**

---

## 📸 Pages Overview

| Page | Description |
|------|-------------|
| 🏠 **Home** | Hero section, course cards, campus grid, facilities, testimonials, CTA |
| 🎓 **Under Graduate** | Full program detail with subjects, highlights, fees, eligibility |
| 📜 **Degree** | Degree programs detail with sidebar info card |
| 🏛️ **Post Graduate** | PG programs with research & professional highlights |
| ✉️ **Contact Us** | Working contact form with validation + info cards |
| ⚙️ **Admin Panel** | Password-protected dashboard to view all form submissions |

---

## ✨ Features

### 🖥️ General
- **Single HTML file** — entire website in one `index.html`, no build step needed
- **SPA routing** — all pages switch instantly using JavaScript (no page reloads)
- **Smooth scroll animations** — cards fade in as you scroll using `IntersectionObserver`
- **Back to Top button** — appears after scrolling 300px, smooth scroll back to top
- **Google Fonts** — Playfair Display + DM Sans for a professional look

### 📱 Mobile Responsive
- Fully responsive across all screen sizes — **desktop, tablet, and mobile**
- **Animated hamburger menu** — three bars (☰) animate into a cross (✕) on tap
- Menu closes automatically when tapping outside, navigating, or resizing to desktop
- Body scroll locks when mobile menu is open
- Responsive breakpoints at **1024px**, **768px**, and **480px**

### 📋 Contact Form
- Client-side **form validation** (required fields, email format check)
- **Saves submissions to `localStorage`** — data persists across browser sessions
- Each submission stores: Name, Email, Phone, Program, Campus, Message, Timestamp
- Success message shown after submission with auto-dismiss after 6 seconds

### ⚙️ Admin Panel
- **Password-protected login** screen
- **Stats dashboard** — total submissions, phone count, top program, campuses
- **Full data table** — all entries with color-coded program badges
- **Delete individual** entries or **Clear All** with confirmation prompt
- **Export as JSON** — download raw data file
- **Export as CSV** — open directly in Excel / Google Sheets

---

## 🗂️ Project Structure

```
rahul-eduford/
│
├── index.html          ← Entire website (HTML + CSS + JS in one file)
└── README.md           ← This file
```

> All CSS and JavaScript is embedded inside `index.html` — no external files needed except Google Fonts (loaded via CDN).

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Clone or Download
```bash
git clone https://github.com/neeraj-4425/rahul-eduford.git
cd rahul-eduford
```

### Step 2 — Add your file
Make sure your file is named `index.html` and is in the **root** of the repository.

### Step 3 — Push to GitHub
```bash
git add .
git commit -m "Add Eduford University website"
git push origin main
```

### Step 4 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select branch: `main` and folder: `/ (root)`
4. Click **Save**
5. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

---

## 🔐 Admin Panel Access

To view submitted contact form entries:

1. Click **⚙ Admin** in the navigation bar
2. Login with the credentials below:

```
Username : admin
Password : eduford123
```

> ⚠️ To change the password, open `index.html` and find this line in the `<script>` section:
> ```javascript
> const ADMIN_CREDS = { user: 'admin', pass: 'eduford123' };
> ```
> Replace with your preferred credentials and save.

---

## 🎨 Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Primary (Navy) | ![#1a3c5e](https://via.placeholder.com/12/1a3c5e/1a3c5e.png) | `#1a3c5e` |
| Accent (Gold) | ![#f4a623](https://via.placeholder.com/12/f4a623/f4a623.png) | `#f4a623` |
| Accent 2 (Orange) | ![#e05c2a](https://via.placeholder.com/12/e05c2a/e05c2a.png) | `#e05c2a` |
| Background | ![#f8f6f1](https://via.placeholder.com/12/f8f6f1/f8f6f1.png) | `#f8f6f1` |
| Text | ![#1a1a2e](https://via.placeholder.com/12/1a1a2e/1a1a2e.png) | `#1a1a2e` |

---

## 🏛️ Campus Locations

- 🏙️ Mumbai
- 🕌 Agra
- 🌿 Uttar Pradesh
- 🏭 Kanpur
- 🌺 Bangalore
- 🌉 Kolkata

---

## 📚 Programs Offered

| Program | Duration | Eligibility | Fees (Annual) | Placement |
|---------|----------|-------------|---------------|-----------|
| Under Graduate | 3–4 Years | 10+2 (50%+) | ₹85,000 – ₹1,20,000 | 96% |
| Degree | 2–5 Years | 10+2 (55%+) / Diploma | ₹90,000 – ₹1,50,000 | 97% |
| Post Graduate | 1–5 Years | UG Degree (50%+) | ₹1,10,000 – ₹2,00,000 | 99% |

---

## 🛠️ Built With

- **HTML5** — Semantic structure, SPA page routing
- **CSS3** — Flexbox, Grid, CSS Variables, clamp(), animations, media queries
- **JavaScript (Vanilla)** — Page routing, form handling, localStorage, IntersectionObserver
- **Google Fonts** — Playfair Display & DM Sans (via CDN)

---

## 📞 Contact Information (Demo)

| Type | Detail |
|------|--------|
| 📍 Address | Andheri East, Mumbai – 400069, Maharashtra |
| 📞 Admissions | +91 98765 43210 |
| 📞 General | +91 22 4567 8900 |
| ✉️ Email | info@eduford.edu |
| 🌐 Website | www.eduford.edu |
| 📸 Instagram | @eduford_university |
| 💼 LinkedIn | Eduford University |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Credits

Made with ❤️ by **Rahul Kumar Rai**

> Inspired by the original [Rahul Eduford](https://neeraj-4425.github.io/rahul-eduford/) design.
