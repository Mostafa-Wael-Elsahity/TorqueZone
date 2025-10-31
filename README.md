# 🚗 TorqueZone – Car Enthusiast Website

TorqueZone is a static, front-end web application designed for car lovers. It showcases iconic automobile brands organized into six major categories, with an elegant UI, modern layouts, and smooth navigation across pages. This project is built with **HTML5**, **CSS3**, and minimal **JavaScript**, focusing on high-performance client-side rendering.

---

## 📌 Features

### ✅ User Experience & Navigation
- Fully navigable multi-page site
- Sticky header with animated nav links
- Footer with newsletter form & social media links
- Hub-based navigation (Homepage → Categories → Category Detail Pages)

### ✅ Car Categories
TorqueZone features six car categories:

| Category | Example Brands |
|---------|----------------|
| Sports Cars | Ferrari, Lamborghini, Porsche |
| Electric Cars | Tesla, Lotus, BYD |
| Classic Cars | Mustang, Corvette, Dodge |
| Luxury Cars | Jaguar, Rolls-Royce, Bentley |
| SUVs | BMW X7, Range Rover, Cadillac |
| Hatchbacks | Golf GTI, Seat, Mini Cooper |

Each category has its own dedicated page and card-style listing.

### ✅ UI Components
- Shared **Header** and **Footer**
- Hero banner with overlay effects
- Category card grid with hover animation
- Call-to-action buttons and top-scroll button

---

## 🏗️ Project Structure

```
TorqueZone/
├── index.html # Homepage
├── html/
│ ├── categories.html
│ ├── sports-logo.html
│ ├── electric-cars-logo.html
│ ├── classic-logo.html
│ ├── luxury-logo.html
│ ├── suv-logo.html
│ ├── hatchback-logo.html
│ ├── aboutus.html
│ ├── contactus.html
│ ├── signup.html
│ ├── login.html
│ └── templete.html
├── css/
│ ├── style.css
│ ├── categories.css
│ ├── header.css
│ ├── footer.css
│ ├── aboutus.css
│ ├── signup.css / login.css
│ └── [category]-logo.css
└── assets/
└── images/
├── logos/
├── categories/
└── car_images/
```


---

## 🎨 Design System

| Element | Style |
|--------|-------|
| Primary Color | `#E50914` (Red) |
| Background | `#111` (Black) |
| Typography | Montserrat (Bold branding font) |
| Components | Card grid, hero banners, sticky navigation |

Interactive effects include:
- Hover elevation + image scale on cards
- Animated underline links
- Dark overlay on hero images

---

## 🧠 Architecture & Patterns

| Approach | Purpose |
|--------|--------|
| Component pattern | Shared header/footer |
| Card-based UI | Category displays |
| 3-tier CSS system | Global + component + page styles |
| Client-side forms | Sign-up, login, contact, newsletter |

> ⚠️ Backend functionality (auth & forms) not yet implemented.

---

## 🚀 How to Run

Simply open **index.html** in any modern browser.  
No build tools required.

```bash
# Clone repository
git clone <repo-link>
cd TorqueZone

# Open index.html in browser
