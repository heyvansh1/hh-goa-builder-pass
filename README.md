# 🌴 Hacker House Goa 2026 — Official Builder Pass Generator

An interactive, client-side web application built for **Hacker House Goa 2026** (28 – 31 Oct 2026). This tool allows Web3 builders, developers, and attendees to generate personalized high-resolution event badges and custom PFP (Profile Picture) overlays directly in their browser.

![HH Goa 2026](https://img.shields.io/badge/Event-Hacker%20House%20Goa%202026-yellow?style=flat-square)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20Canvas%20API-emerald?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-pink?style=flat-square)

---

## ✨ Features

* **Dual Format Generator:**
  * **Format B (Official Builder Pass):** High-resolution vertical event badge ($1000 \times 1650\text{ px}$) complete with lanyard slots, branding elements, $50K+ bounty signs, customizable name, and role/stack.
  * **Format A (PFP Overlay):** Square avatar overlay ($1000 \times 1000\text{ px}$) with circular masking, gold border rings, and date tags for X/Twitter profiles.
* **Smart Image Adjustments:**
  * Real-time **Zoom** and **Pan (X/Y)** sliders for precise photo positioning.
  * Support for standard image formats (`JPG`, `PNG`) and native iPhone photos (`HEIC`/`HEIF`) converted on the fly.
  * Drag-and-drop file upload zone.
* **Instant Social Sharing & Export:**
  * One-click high-resolution PNG download.
  * Direct Twitter/X sharing integration with the official `#FrameInGoa` hashtag.

---

## 🚀 Live Demo

Check out the live generator hosted via GitHub Pages:  
👉 **[https://heyvansh1.github.io/hh-goa-builder-pass/](https://heyvansh1.github.io/hh-goa-builder-pass/)**

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, HTML5 Canvas API
* **Styling:** Tailwind CSS (via CDN)
* **Image Processing:** `heic2any` (Client-side HEIC to JPEG conversion)
* **Fonts:** Google Fonts (`Playfair Display`, `Plus Jakarta Sans`, `JetBrains Mono`, `VT323`, `Rozha One`)

---

## 📦 Local Development

Since this project runs entirely on client-side code, no build setup or backend server is required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/heyvansh1/hh-goa-builder-pass.git](https://github.com/heyvansh1/hh-goa-builder-pass.git)
