# World Vision Cable Network

> Premium Digital TV, High-Speed FTTH Fiber Broadband, and Strategic Partner Plans (JioFiber & BSNL Bharat Fiber).

World Vision Cable Network is a modern, responsive, multi-page web application designed for a regional telecommunications and digital cable television service provider. It delivers a fast, user-friendly portal for customers to explore television channel packages, high-speed fiber broadband tiers, partner bundles with JioFiber and BSNL, pay bills online, and request same-day doorstep connections.

---

## 🌟 Key Features

- **Modern & Responsive UI**: Built with a sleek design system inspired by telecom leaders, featuring glassmorphism cards, dynamic gradients, network status indicators, and clean typography.
- **Full Service Catalog**: Showcases standalone Digital TV packages, high-speed FTTH plans, authorized JioFiber & BSNL Bharat Fiber connections, and value-packed TV + Internet bundles.
- **Quick Bill Payment & Recharge**: Dedicated quick-pay portal interface supporting VC / Customer ID lookup with payment methods including UPI, QR code, debit/credit cards, and net banking.
- **Lead Capture & Booking Form**: Interactive connection booking form with service selection, address details, and rapid callback SLA guarantees.
- **Customer Support & Instant WhatsApp Connectivity**: Direct click-to-call phone links, direct WhatsApp instant chat, 24/7 helpline badges, and field-technician SLA guarantees.
- **Coverage Map**: Clear display of 60+ local coverage areas and neighborhoods served by redundant fiber optic loops.

---

## 📁 Project Structure

```text
testproject/
│
├── index.html          # Homepage: Hero section, live status, speed highlights, partner showcase, FAQs
├── services.html       # Services & Plans: Digital TV, Fiber Broadband, Jio & BSNL partner plans, combos
├── about.html          # About Us: Heritage (15+ yrs, 25K+ subscribers), infrastructure, mission, timeline
├── contact.html        # Contact & Booking: Booking form, quick bill pay, helpline numbers, coverage areas
│
├── css/
│   └── style.css       # Custom design system: Color tokens, CSS variables, cards, navbar, buttons, footer
│
├── images/
│   ├── logo.png        # Primary brand logo
│   └── logo-original.png # High-resolution source logo asset
│
└── README.md           # Project documentation and setup guide
```

---

## 🛠️ Technology Stack

| Layer | Technology | Details |
|---|---|---|
| **Structure** | HTML5 | Semantic HTML markup with SEO meta tags, OpenGraph data, and mobile viewports |
| **Styling** | Vanilla CSS3 | Custom design system (`css/style.css`) using CSS custom properties (variables) |
| **Framework** | Bootstrap 5.3.3 | Grid layout, responsive utility classes, navigation collapse, and dropdowns |
| **Icons** | Bootstrap Icons 1.11.3 | Scalable vector icons for telecom, TV, speed, and contact elements |
| **Typography** | Google Fonts | [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (weights 300 to 800) |
| **Design Aesthetics** | Custom Modern CSS | Glassmorphism, smooth hover micro-animations, radiant gradients |

### Color Palette
- **Ink Black (`--ink-black`, `--dark`)**: `#011627` (Deep modern navy-black for headings, hero backgrounds, and dark footer)
- **Porcelain (`--porcelain`, `--white`)**: `#FDFFFC` (Crisp, clean neutral background and card surface)
- **Light Sea Green (`--light-sea-green`, `--teal`, `--blue`)**: `#2EC4B6` (Primary vibrant brand color for links, speeds, and icons)
- **Punch Red (`--punch-red`, `--red`, `--danger`)**: `#E71D36` (High-energy accent for live pulse alerts, ribbons, and badges)
- **Amber Glow (`--amber-glow`, `--orange`, `--warning`)**: `#FF9F1C` (Radiant warm accent for CTA buttons, ratings, and highlights)

---

## 📄 Page Overviews

### 1. `index.html` (Home)
- **Hero Banner**: Live network status indicator ("Network Live & Stable"), speed gauge graphic, and primary call-to-actions.
- **Partner Highlights**: Co-branding banners for JioFiber and BSNL Bharat Fiber.
- **Service Highlights**: 450+ High Definition channels, gigabit fiber broadband, and smart Android STB upgrades.
- **Customer Testimonials & FAQs**: Social proof and answers to common subscriber questions.

### 2. `services.html` (Plans & Pricing)
- **Anchor Navigation Pills**: Quick jump to specific categories (Digital TV, World Vision Fiber, JioFiber, BSNL Fiber, Combos).
- **Digital TV Plans**: Silver (250 channels), Gold (350 channels), and Platinum HD (450+ channels), plus hardware box details (HD Standard vs. 4K Android Smart Box).
- **Fiber Internet Plans**: Speed tiers ranging from 50 Mbps up to 300 Mbps with unlimited symmetrical data.
- **Partner & OTT Bundles**: Plans bundled with top OTT applications (Netflix, Disney+ Hotstar, Amazon Prime Video, SonyLIV, ZEE5, JioCinema).

### 3. `about.html` (About Company)
- **Company Heritage**: Over 15 years of operational excellence and 25,000+ satisfied households.
- **Core Pillars**: Uninterrupted fiber backbone, 2-hour field technician dispatch SLA, weather-resistant digital feed, and transparent billing.
- **Milestones Timeline**: Evolution from local cable operator to fiber-optic partner of India's telecom giants.

### 4. `contact.html` (Support & Booking)
- **Direct Support Channels**: Dedicated customer care phone numbers, 1-click WhatsApp chat, and official support email.
- **Connection Booking Form**: Form allowing prospective customers to choose services, speed tier, and input service address.
- **Quick Pay & Recharge**: Self-service subscription renewal section accepting UPI, QR code, debit/credit card, and net banking.
- **Coverage Map**: Neighborhood checklist covering over 60 active zones.

---

## 🚀 How to Run & Preview

Because this is a pure static web application, no compilation or build steps are required.

### Option 1: Direct File Open
Double-click `index.html` in your file explorer, or right-click and choose **Open with > Chrome / Edge / Firefox**.

### Option 2: Using Python HTTP Server
If Python is installed on your computer:
```bash
# Navigate to the project root
cd path/to/testproject

# Start a local web server (Python 3)
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

### Option 3: Using Node.js (`npx serve`)
If Node.js is installed:
```bash
npx serve .
```

### Option 4: VS Code / IDE Live Server
Right-click on `index.html` and click **"Open with Live Server"**.

---

## ⚙️ Customization Guide

- **Updating Contact Numbers / Email**:
  Search for `+91 88609 81712`, `+91 97168 04910`, and `support@worldvisioncable.com` across the HTML files to update phone numbers and email addresses.
- **Changing Logos**:
  Replace `images/logo.png` with your updated company logo while keeping the aspect ratio consistent.
- **Modifying Plan Prices & Channels**:
  Edit the pricing cards inside `services.html` under their respective section IDs (`#digital-tv`, `#fiber-broadband`, `#jio-broadband`, etc.).
- **Theme Colors**:
  Update color variables in `:root` in `css/style.css` to change the primary brand colors globally.

---

## 📱 Browser Compatibility

- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Apple Safari (macOS & iOS)
- Mobile browsers (Chrome Android, Safari iOS, Samsung Internet)

---

## 📞 Support & Helpline

- **Helpline 1**: +91 88609 81712
- **Helpline 2**: +91 97168 04910
- **Email**: support@worldvisioncable.com
- **Operating Hours**: 24/7 Local Helpdesk & Doorstep Technician Support
