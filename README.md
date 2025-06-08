# 🌐 Dimention – Modern Collaboration Landing Page

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-brightgreen)
![Status](https://img.shields.io/badge/Project-Demo--Ready-blue)

Dimention is a sleek and modern landing page tailored for developer collaboration platforms. Featuring interactive UI, animated buttons, and a fully simulated chat dashboard, it’s built to impress both users and stakeholders.

---

## 🚀 Features

### 🧭 Navigation Bar
- Fixed top navigation
- Brand logo with links to: About, Careers, Blog, Changelog
- Stylish `Join Waitlist` call-to-action button

### 💬 Hero Section
- Big, bold headline with animated gradient text
- Email input with a multistroke CTA button
- Animated rotating circles for visual depth
- Announcement badge with gradient background

### 📥 Email Waitlist Signup
- Clean input field with call-to-action
- Stylish animations using Tailwind and custom gradients

### 💻 Chat Interface (Desktop only)
> Full-featured mock UI simulating a real app dashboard:
- **Sidebar:** Team & direct message sections with collapsible accordions
- **Main Chat Window:** User avatars, messages, timestamps, task references
- **Right Panel:** Team member list, task tracker, deployment summary

### 🖼️ Brand Showcase
- Logos of top open-source projects like Million.js, SolidJS, Astro, etc.

### 🔋 CTA Card with Gradient Stroke
- Emphasizes collaboration
- Avatars representing multiple contributors
- Code snippet with live cursors for realism

---

## 📱 Responsive Design

Built mobile-first using Tailwind’s responsive classes:

| Device        | Behavior                         |
|---------------|----------------------------------|
| **Mobile**    | Compact layout, hidden dashboard |
| **Tablet**    | Adaptive text and layout         |
| **Desktop**   | Full dashboard + animations      |

✅ Uses `sm:`, `md:`, `lg:` breakpoints  
✅ Conditional visibility (`hidden`, `block`, `flex`)  
✅ Adaptive padding/margin and typography

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS**
- **Google Fonts** – `Inter`
- **Custom CSS Variables**
- **SVG Icons & Gradients**

---

## 📂 Suggested Structure

```txt
project/
├── index.html
├── images/
│   └── logo.png, profile.png, etc.
├── styles/
│   └── tailwind.css or main.css
