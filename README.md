# Digital Portfolio

> 🚧 **Status: actively being developed and maintained.** New sections, features and fixes are added regularly.

This is my personal portfolio website. It's built from scratch with plain HTML, CSS and JavaScript, with no frameworks or build tools. It will show my work, my tech stack, and my path as a Year 2 Computing and IT student, plus a way to get in touch.

While the main site is being built, a **maintenance page** is live that tells visitors the site is being updated and links to my contact channels.

---

## ✨ Features

### Maintenance page (`maintenance.html`)
- **"Under maintenance" badge**: a pill-shaped status badge with an amber indicator dot.
- **Fluid headline**: the "Back shortly." heading scales with the screen using `clamp()`.
- **Terminal-style deploy log**: a styled terminal window with window buttons and a fake deploy log (`building... done`, `running tests... done`, `publishing... in progress`) in a monospace font with green and amber status colours.
- **Contact links**: buttons for Email, GitHub and LinkedIn so visitors can still reach me.
- **Status footer**: shows name, `503` status and "Back Shortly", and stays at the bottom of the screen on every device.

### Site-wide design
- **Sticky navigation bar** with a frosted-glass effect (`backdrop-filter: blur`), the logo, and links to *Work*, *Stack*, *Path* and *Ping*.
- **Dark theme** with a fixed grid background drawn entirely in CSS gradients (no images).
- **Custom typography** from Google Fonts:
    - **Syne**: headings and display text
    - **DM Mono**: navigation, terminal and footer
    - **IBM Plex Sans**: body text and buttons
- **Consistent colour palette**: near-black background (`#0A0B0A`), off-white text (`#EDEFEA`), neon green accent (`#7FFF6E`) and amber highlights (`#E3C77E`).

### Responsive layout
- **Desktop**: content capped at a readable width (640px on the maintenance page) and centred.
- **Tablet (≤ 900px)**: reduced side padding for the nav and footer.
- **Mobile (≤ 600px)**: tighter spacing and smaller text, with the footer content kept on the left and right edges.
- Flexbox layout keeps the footer at the bottom of the screen, even when there's little content.

---

## 🛠️ Built With

| Technology   | Purpose |
|--------------|---------|
| HTML5        | Page structure and semantic markup |
| CSS3         | Styling, Flexbox layout, media queries, gradients |
| JavaScript   | Interactivity (planned, `js/main.js`) |
| Google Fonts | Syne, DM Mono, IBM Plex Sans |

---

## 📁 Project Structure

```
Digital_Portfolio/
├── index.html          # Main portfolio page (in progress)
├── maintenance.html    # "Back shortly" maintenance page
├── css/
│   └── style.css       # All site styles, including responsive media queries
├── js/
│   └── main.js         # JavaScript for interactivity (coming soon)
├── images/             # Logo and favicon
├── videos/             # Video assets (planned)
├── Extras/             # Font files and extra favicon sizes
└── README.md
```

---

## 🚀 Running Locally

No installation or build step is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/aiman-nwz/Digital_Portfolio.git
   ```
2. Open `maintenance.html` or `index.html` in your browser.

   Or use an editor's built-in preview (e.g. WebStorm, or VS Code with Live Server) to reload automatically as you edit.

---

## 🗺️ Roadmap

- [x] Navigation bar and site-wide dark theme
- [x] Grid background design
- [x] Responsive maintenance page with terminal-style deploy log
- [x] Responsive footer
- [ ] **Work**: project showcase section
- [ ] **Stack**: languages, tools and technologies I use
- [ ] **Path**: education and experience timeline
- [ ] **Ping**: contact section
- [ ] JavaScript interactivity and animations
- [ ] Deploy the full site

---

## 📌 Project Status

This project is **actively being developed and maintained**. The maintenance page is complete, and the main portfolio (`index.html`) is being built section by section. Expect frequent updates to the design, content and features.

---

## 📬 Contact

**Aiman Nawaz**, Year 2 Computing and IT student · Open to internships

- GitHub: [@aiman-nwz](https://github.com/aiman-nwz)
- LinkedIn: [aiman-nwz](https://linkedin.com/in/aiman-nwz)