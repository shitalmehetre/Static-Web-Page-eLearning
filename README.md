# 📚 eLearning — Static HTML Website

A clean, responsive **static website** built with pure HTML and CSS for an online learning platform. The site includes four pages: Home, About, Courses, and Contact.

---

## 📁 Project Structure

```
eLearning/
│
├── index.html          # Home page with hero banner
├── about.html          # About Us page
├── courses.html        # Popular Courses listing page
├── contact.html        # Contact page with map & form
│
├── CSS/
│   └── style.css       # Global stylesheet for all pages
│
└── Images/
    ├── carousel-1.jpg  # Hero/banner background image
    ├── about.jpg       # About section image
    ├── courses.jpg     # Courses section image
    ├── course-1.jpg    # Web Design & Development course image
    ├── course-2.jpg    # Graphic Design course image
    └── course-3.jpg    # Video Editing course image
```

---

## 🌐 Pages Overview

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero section with call-to-action buttons |
| About | `about.html` | Platform introduction with image and feature links |
| Courses | `courses.html` | Three course cards with pricing and details |
| Contact | `contact.html` | Contact info, Google Map embed, and contact form |

---

## ✨ Features

- **Responsive Navigation** — Fixed top header with logo, nav links, search bar, and "Join Now" button
- **Hero Banner** — Full-width background image with overlay and call-to-action buttons
- **Course Cards** — Image, price, instructor, duration, and action buttons per course
- **About Section** — Two-column layout with image and descriptive content
- **Contact Page** — Three-column layout: contact info | Google Map | contact form
- **Footer** — Four-column footer with Quick Links, Contact info, Image Gallery, and Newsletter signup
- **Active Link Highlighting** — Current page is highlighted in the navigation bar
- **Hover Effects** — Buttons and links have smooth color transitions

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, and responsiveness |
| Google Maps Embed | Interactive map on Contact page |
| Google Fonts (Nunito) | Typography (referenced in CSS) |

> ⚠️ No JavaScript frameworks or build tools are required. This is a pure static HTML/CSS project.

---

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No server or installation required

### Running Locally

1. **Clone or download** the project folder
2. Make sure the folder structure is maintained exactly as shown above
3. Open `index.html` in your browser:

```bash
# Option 1: Double-click index.html in File Explorer

# Option 2: Using VS Code Live Server extension
code .
# Then right-click index.html → "Open with Live Server"

# Option 3: Using Python's built-in server
python -m http.server 8000
# Visit http://localhost:8000 in your browser
```

---

## 🎨 Color Palette

| Color Name | Hex Code | Used For |
|-----------|----------|----------|
| Primary Blue | `#007bff` | Logo, nav active, Join button |
| Cyan Accent | `#06BBCC` | Section titles, badge text |
| Dark Teal | `#00c4cc` | Course buttons, icon boxes |
| Dark Navy | `#1a1a2e` | Footer background |
| Light Gray | `#f8f9fa` | Body and card backgrounds |

---

## 📱 Responsive Design

The layout adapts for smaller screens:

- **Below 900px** — Header stacks vertically; footer columns stack in a single column
- **Below 768px** — About section switches from two-column to single-column layout
- **1200px+** — Hero heading font scales up to `4rem` for large displays

---

## 📄 Page Details

### 🏠 Home (`index.html`)
- Full-screen hero with background image and dark overlay
- "Best Online Courses" tagline + two CTA buttons: **Read More** and **Join Now**

### ℹ️ About (`about.html`)
- Breadcrumb navigation below hero
- Two-column section: left image, right text with course feature links
- Styled `ABOUT US` section heading with decorative lines

### 📖 Courses (`courses.html`)
- Three course cards in a table layout
- Each card shows: course image, price, title, instructor, duration, student count
- **Read More** and **Join Now** action buttons per card

### 📬 Contact (`contact.html`)
- Three-column layout:
  - **Left** — Address, phone, email with colored icon boxes
  - **Center** — Embedded Google Map (New York, USA)
  - **Right** — Contact form (Name, Email, Subject, Message, Send button)

---

## 🔗 Navigation Links

All pages share the same header and footer. Internal links are:

```
index.html   →  Home
about.html   →  About
courses.html →  Courses
contact.html →  Contact
```

---

## 🖼️ Image Requirements

Ensure the following images are placed inside the `Images/` folder:

| File | Dimensions (recommended) | Used On |
|------|--------------------------|---------|
| `carousel-1.jpg` | 1920×500px | All pages (hero background) |
| `about.jpg` | 600×500px | About page |
| `course-1.jpg` | 600×400px | Courses page & footer gallery |
| `course-2.jpg` | 600×400px | Courses page & footer gallery |
| `course-3.jpg` | 600×400px | Courses page & footer gallery |

---

## 🔧 Known Limitations & Improvement Suggestions

| Issue | Suggestion |
|-------|-----------|
| Search bar is non-functional | Connect to a backend or use a JS-based filter |
| Contact form has no backend | Integrate with Formspree, EmailJS, or a server-side handler |
| `<input>` inside `<ul>` is invalid HTML | Move search inputs outside the `<ul>` tag |
| Tables used for layout | Replace with CSS Flexbox or Grid for better responsiveness |
| No `<!DOCTYPE html>` in `index.html` | Add `<!DOCTYPE html>` at the top |
| Images in footer gallery are small and fixed | Make gallery responsive with CSS Grid |

---

## 📜 License

This project is for **educational/demo purposes** only.  
© 2025 eLearning. All Rights Reserved.

---

## 👨‍💻 Author

Developed as a static HTML/CSS frontend template for an eLearning platform.  
Feel free to customize and extend it as needed.
