# 🌿 Mane Craft Studio

> **Natural health for your hair** — An exclusive boutique hair care studio specializing in artisan styling, natural therapies, and 100% vegan hair treatments.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-6.7.2-528DD7?style=flat&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![Responsive](https://img.shields.io/badge/Design-Responsive-69B99D?style=flat)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Website Sections](#-website-sections)
- [Contact Details & Alternative Information](#-contact-details--alternative-information)
- [Design & Typography](#-design--typography)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customization Guide](#-customization-guide)
- [Browser Compatibility](#-browser-compatibility)
- [Credits & License](#-credits--license)

---

## 🌟 Overview

**Mane Craft Studio** is a clean, modern, and responsive website crafted for a premier salon dedicated to conscious hair health. The website highlights the studio's organic methodology, experienced team of stylists, customer satisfaction, and easy appointment scheduling across multiple communication channels.

### Key Highlights:
- **Artisan Hair Care**: Showcases natural hair therapies, precision cuts, and organic vegan treatments.
- **Modern Responsive Layout**: Built with mobile-friendly flexbox structures, sticky navigation, and smooth scroll behaviors.
- **Enhanced Contact Options**: Complete primary and alternative contact details (phone, email, WhatsApp, and studio hours).
- **Lightweight & Fast**: Pure HTML5 and CSS3 without heavy JavaScript dependencies.

---

## 🖥️ Website Sections

1. **Header & Navigation (`#header`)**:
   - Sticky header with the **Mane Craft Studio** vector logo.
   - Smooth anchor navigation linking to `Home`, `About`, `Services`, `Testimonials`, and `Contact`.

2. **Hero Section (`#hero`)**:
   - Bold headline and introduction to the studio's natural philosophy.
   - Quick call-to-action button leading directly to appointment scheduling.

3. **About Us (`#about`)**:
   - Detailed story behind Mane Craft Studio's dedication to sustainable, vegan, and scalp-nourishing hair care.
   - High-quality visual representation of the studio space and care rituals.

4. **Services (`#services`)**:
   - Interactive service cards with hover lift animations:
     - **Hair Therapy**: Scalp restoration and nourishing botanicals for all hair textures.
     - **Artisan Cuts**: Trendsetting precision styling and tailored cuts.
     - **Natural Treatments**: 100% vegan treatments customized for strength and shine.

5. **Client Testimonials (`#clients`)**:
   - Real client reviews with quote styling and client avatars.

6. **Contact & Booking (`#contact`)**:
   - Direct WhatsApp booking button.
   - Structured contact cards with primary and alternative contact channels.

7. **Footer (`#footer`)**:
   - Inverted brand logo, copyright information, and social media links (Instagram, Facebook, YouTube).

---

## 📞 Contact Details & Alternative Information

The contact section has been configured with comprehensive, labeled primary and alternative communication channels:

| Contact Method | Type | Detail / Link |
| :--- | :--- | :--- |
| **Phone** | Primary | [`+1 (555) 234-5678`](tel:+15552345678) |
| **Phone** | Alternative (Bookings) | [`+1 (555) 890-4321`](tel:+15558904321) |
| **Email** | Primary | [`contact@manecraftstudio.com`](mailto:contact@manecraftstudio.com) |
| **Email** | Alternative (Support) | [`appointments@manecraftstudio.com`](mailto:appointments@manecraftstudio.com) |
| **Studio Location** | Physical Address | `142 Artisan Boulevard, Suite 200, Craft District, NY 10012` |
| **Studio Hours** | Operating Hours | `Mon – Sat: 9:00 AM – 7:30 PM \| Sunday: By Appointment` |
| **WhatsApp** | Direct Messaging | [`Chat on WhatsApp`](https://wa.me/15552345678?text=Hello%20Mane%20Craft%20Studio!%20I'd%20like%20to%20schedule%20an%20appointment.) |

---

## 🎨 Design & Typography

- **Primary Color**: `#69B99D` (Artisan Sage Green)
- **Dark Neutral**: `#0F241D` (Deep Forest Green / Near Black)
- **Light Background**: `#F7F7F7` & `#F9F9F9` (Clean Studio Off-White)
- **Text Color**: `#767676` / `#555555`
- **Typography**:
  - Headings: `Poppins` (Google Fonts, Bold 700 / 800)
  - Body Text: `DM Sans` (Google Fonts, Regular 400 / Medium 500)

---

## 📁 Project Structure

```text
ManeCraft-Studio/
├── .vscode/
│   └── settings.json          # Live Server configuration (Port 5501)
├── css/
│   └── main.css               # Core styling, responsive layouts & typography
├── images/
│   ├── favicon.svg            # Mane Craft Studio favicon
│   ├── logo.svg               # Header vector logo
│   ├── footer-logo.svg        # Footer vector logo
│   ├── hero-image.png         # Hero banner image
│   ├── about-image.png        # About section feature image
│   ├── service-1.png          # Hair therapy card icon
│   ├── service-2.png          # Artisan cuts card icon
│   ├── service-3.png          # Treatments card icon
│   ├── client-1.png           # Testimonial avatar 1
│   ├── client-2.png           # Testimonial avatar 2
│   ├── logo.png               # Brand logo (fallback)
│   ├── footer-logo.png        # Footer logo (fallback)
│   └── -1.png                 # Legacy asset
├── index.html                 # Main website markup
└── README.md                  # Project documentation
```

---

## 🚀 Getting Started

### 1. View Locally in a Browser
You can open `index.html` directly in any web browser:
- Double-click `index.html` in Windows File Explorer, or
- Right-click and choose **Open with > Google Chrome / Microsoft Edge / Firefox**.

### 2. Using VS Code Live Server
The project is preconfigured for VS Code's **Live Server** extension:
1. Open the project folder in VS Code.
2. Click **Go Live** in the bottom status bar, or right-click `index.html` and select **Open with Live Server**.
3. The site will launch automatically at:
   ```text
   http://127.0.0.1:5501/index.html
   ```

### 3. Using Node.js (Optional)
If you have Node.js installed, you can launch a local development server using `npx`:
```bash
# Using serve
npx serve .

# Or using http-server
npx http-server -p 5501
```

---

## 🛠️ Customization Guide

### Updating Brand Name or Logo
- **HTML Title & Headings**: Search for `Mane Craft Studio` in `index.html` to update page headings or titles.
- **Logos**: Vector logos are stored in `images/logo.svg` (header) and `images/footer-logo.svg` (footer). You can adjust SVG colors, font weights, and text directly in the SVG files.

### Modifying Contact Information
Locate the `<section class="contact" id="contact">` block in `index.html`:
- Update phone numbers in both the text and the `href="tel:..."` attribute.
- Update emails in both the text and the `href="mailto:..."` attribute.
- Update the WhatsApp number and default message in the `https://wa.me/...` link.

---

## 🌐 Browser Compatibility

Tested and fully compatible with:
- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Apple Safari (latest)
- Mobile Browsers (iOS Safari, Android Chrome)

---

## 📄 License & Credits

- **Website Development**: Built for **Mane Craft Studio**.
- **Icons**: [Font Awesome](https://fontawesome.com/)
- **Fonts**: [Google Fonts](https://fonts.google.com/) (`Poppins` and `DM Sans`)
- **Copyright**: &copy; 2026 Mane Craft Studio. All rights reserved.

