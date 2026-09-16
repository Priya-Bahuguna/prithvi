# 🌍 Prithvi

### Our Planet, Our Responsibility

## 🌿 About the Project

**Prithvi** (प्रिथ्वी, meaning *"Earth"*) is an environmental awareness website that
brings together information on natural resources, pollution, sustainability, and
India's traditional connection with nature — all wrapped in a warm, forest-toned
design system.

It's also built to double as a **reference project**: nearly every common HTML
element and a wide range of CSS techniques (Flexbox, Grid, pseudo-classes,
`:has()`, the checkbox hack, CSS-only tabs/lightbox/accordion, custom
properties, and more) are demonstrated across its pages — with **no JavaScript
required anywhere.**

---

## ✨ Features

| | |
|---|---|
| 🌗 | **Light & Dark mode** — pure CSS toggle, fully adaptive colors |
| 📱 | **Fully responsive** — works from mobile to desktop |
| 🖼️ | **CSS-only lightbox gallery** — no JS, just `:target` |
| 📁 | **Accordion FAQ** — native `<details>`/`<summary>` |
| 🗂️ | **Tabbed content** — CSS radio-button hack |
| 📊 | **Data tables** — rowspan, colspan, captions |
| 📈 | **Live progress bars & meters** — `<progress>` / `<meter>` |
| 📝 | **Full-featured survey form** — every common input type |
| 🎬 | **Audio, video & embedded iframe** support |
| ♿ | **Accessible** — semantic HTML, focus states, reduced-motion support |
| 🖨️ | **Print-friendly** styles included |

---

## 📄 Pages

| Page | File | What's inside |
|---|---|---|
| 🏠 Home | `index.html` | Hero section, quick stats, navigation hub |
| 🌎 About Earth | `about.html` | Resources, key terms, tabs, text formatting |
| ⚠️ Environment | `environment.html` | Environmental problems, quotes, sources |
| 🕉️ Culture | `culture.html` | India's traditional ties to nature |
| 🖼️ Gallery | `gallery.html` | Photo gallery with CSS-only lightbox |
| 📊 Statistics | `statistics.html` | Tables, progress bars, meters |
| 🎧 Media | `media.html` | Audio, video, external links, iframe |
| ❓ FAQ | `faq.html` | Accordion-style frequently asked questions |
| 📝 Survey | `survey.html` | Full HTML form covering every input type |
| ✉️ Contact | `contact.html` | Address, contact details, downloadable info |

---

## 🎨 Design System

Prithvi uses a **nature-grounded palette** — forest greens, bark browns, and
river blues — defined entirely through CSS custom properties, so switching
themes or updating brand colors takes seconds.

```
🌲 Forest Deep   #16302a       🍃 Moss         #52b788
🌳 Forest Mid    #2d6a4f       🌾 Sand         #f2ecdd
🏞️ River         #3d7a94       🌅 Sunrise      #e0a458
```

**Typography:** [Fraunces](https://fonts.google.com/specimen/Fraunces) for
headings, [Work Sans](https://fonts.google.com/specimen/Work+Sans) for body
text.

---

## 🚀 Getting Started

No build tools, no installs, no dependencies. Just open it and go.

```bash
# 1. Clone or download this project
# 2. Open index.html in any modern browser
```

That's it — the whole site runs from static files.

---

## 📁 Project Structure

```
prithvi/
├── index.html          # Home page
├── about.html
├── environment.html
├── culture.html
├── gallery.html
├── statistics.html
├── media.html
├── faq.html
├── survey.html
├── contact.html
├── css/
│   └── style.css       # Full design system + dark mode
└── README.md
```

---

## 🌗 Dark Mode

Toggle **Night mode** from the header on any page. All headings, body text,
links, cards, tables, and forms adapt automatically — no flash, no JavaScript,
just CSS custom properties flipping on a checkbox toggle.

---

## 🤝 Contributing / Customizing

Everything is driven by CSS variables in `css/style.css`, so you can easily:

- 🎨 Re-theme the whole site by changing the color tokens in `:root`
- ✏️ Edit page content directly in each `.html` file
- ➕ Add a new page by copying the shared header/footer markup

---

