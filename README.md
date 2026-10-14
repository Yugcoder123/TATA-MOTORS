<div align="center">

# 🚗 Tata Motors: Online Brochure

### My first website. A digital showroom for Tata's car lineup.

*Built from scratch with pure HTML & CSS. No frameworks, no shortcuts, just a lot of learning.*

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)

![Pages](https://img.shields.io/badge/pages-9-blue?style=flat-square)
![Cars](https://img.shields.io/badge/car%20models-7-red?style=flat-square)
![Status](https://img.shields.io/badge/project-my%20first%20website-brightgreen?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blueviolet?style=flat-square)

[✨ Features](#-features) • [🚘 The Lineup](#-the-lineup) • [🚀 Quick Start](#-quick-start) • [📁 Structure](#-project-structure) • [🗺️ Roadmap](#️-roadmap) • [⚠️ Disclaimer](#️-disclaimer)

</div>

---

## 🏁 About

Every developer has a first project, and this is mine.

**Tata Motors Online Brochure** is a multi-page website that showcases Tata's popular cars: a home page with the full lineup, a dedicated "Know More" page for each model, and an order page to book your pick. It was my first attempt at building a real, multi-page website, and it taught me how HTML structure, CSS layout and page-to-page navigation all fit together.

---

## ✨ Features

| | Feature | Details |
|---|---------|---------|
| 🏠 | **Showcase home page** | All seven models with a photo, description and two action buttons |
| 📄 | **Dedicated model pages** | A "Know More" page for every car with detailed sections |
| 🧭 | **Smooth in-page navigation** | A top navbar that jumps straight to any car on the home page |
| 🔍 | **Deep-dive sections** | Design, Safety, Performance, Tech and Comfort, each with its own images |
| 📝 | **Order page** | A booking form with a car selector dropdown |
| 🔄 | **Alternating layouts** | Image and text swap sides for each car, keeping the page lively |
| 📱 | **Responsive detail pages** | Layout adapts for tablets and phones using media queries |
| 🌐 | **Social links** | Footer icons linking to Tata Motors on Facebook, X and Instagram |

---

## 🚘 The Lineup

| # | Model | Type | Page |
|:-:|-------|------|------|
| 1 | **Safari** | SUV | [`safari.html`](safari.html) |
| 2 | **Harrier** | SUV | [`harrier.html`](harrier.html) |
| 3 | **Nexon** | Compact SUV | [`nexon.html`](nexon.html) |
| 4 | **Altroz** | Hatchback | [`altroz.html`](altroz.html) |
| 5 | **Punch** | Micro SUV | [`punch.html`](punch.html) |
| 6 | **Tigor** | Sedan | [`tigor.html`](tigor.html) |
| 7 | **Tiago** | Hatchback | [`tiago.html`](tiago.html) |

---

## 🖼️ Preview

<!-- 📸 Add screenshots of your pages here: -->
<!-- ![Home Page](images/screenshot-home.png) -->
<!-- ![Nexon Page](images/screenshot-nexon.png) -->

*Screenshots coming soon.*

---

## 🗺️ Site Map

```
                    ┌──────────────┐
                    │  index.html  │  ← Home: the full lineup
                    └──────┬───────┘
         ┌────────┬────────┼────────┬────────┬────────┬────────┐
         ▼        ▼        ▼        ▼        ▼        ▼        ▼
      safari   harrier   nexon   altroz   punch    tigor    tiago
      .html    .html     .html   .html    .html    .html    .html
         │        │        │        │        │        │        │
         └────────┴────────┴────┬───┴────────┴────────┴────────┘
                                ▼
                         ┌─────────────┐
                         │ order.html  │  ← Book your car
                         └─────────────┘
```

Every car on the home page has two buttons: **ORDER NOW** (jumps to the order page) and **KNOW MORE** (opens that model's detail page).

---

## 🚀 Quick Start

No installs, no setup. It's a static website.

```bash
# 1. Clone the repo
git clone https://github.com/Yugcoder123/TATA-MOTORS.git

# 2. Step inside
cd TATA-MOTORS

# 3. Open the home page in your browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

> 💡 **No terminal?** Download the ZIP from GitHub, unzip it and double-click `index.html`.

### 🌍 Put it online with GitHub Pages

1. Go to your repo's **Settings → Pages**
2. Under **Source**, choose the `main` branch and the `/ (root)` folder
3. Click **Save**. Your site will be live at `https://yugcoder123.github.io/TATA-MOTORS/` in a minute or two

---

## 📁 Project Structure

```
TATA-MOTORS/
├── 📄 index.html          → Home page with the full lineup
├── 📄 safari.html         → Safari details
├── 📄 harrier.html        → Harrier details
├── 📄 nexon.html          → Nexon details
├── 📄 altroz.html         → Altroz details
├── 📄 punch.html          → Punch details
├── 📄 tigor.html          → Tigor details
├── 📄 tiago.html          → Tiago details
├── 📄 order.html          → Order / booking form
├── 🎨 style.css           → Styles for the home page
├── 🎨 know.css            → Styles for the model detail pages
├── 🎨 order.css           → Styles for the order page
├── 🖼️ cars.jpg            → Hero / cover image
├── 📂 images/             → Logo, favicon and home page car photos
└── 📂 *-images/           → Photo folders for each model
    ├── safari images/
    ├── harrier images/
    ├── nexon images/
    ├── atroz images/
    ├── punch images/
    ├── tigor images/
    └── tiago images/
```

---

## 🛠️ Built With

| Technology | Used for |
|------------|----------|
| **HTML5** | Page structure, forms and navigation |
| **CSS3** | Flexbox layouts, buttons, media queries |
| **Google Fonts** (Poppins) | Typography |
| **Font Awesome 6** | Social media icons |

---

## 💡 What I Learned

- Structuring a **multi-page website** and linking pages together
- Building layouts with **Flexbox**, including alternating image/text rows with `row-reverse`
- Using **anchor links** (`#id`) for smooth jumping within a page
- Writing **media queries** so pages adapt to smaller screens
- Organizing images into folders and keeping a project tidy

---

## 🗺️ Roadmap

- [ ] 📱 Make the home and order pages fully responsive
- [ ] ✅ Add form validation and a "thank you" confirmation to the order page
- [ ] 🔗 Fix and polish navigation links across pages
- [ ] 🖼️ Add an image gallery or slider to each model page
- [ ] 💰 Add variant and price comparison tables
- [ ] 🌙 Light / dark theme toggle
- [ ] ✨ Hover effects and subtle animations
- [ ] 🔍 Add proper `alt` text to images for accessibility and SEO

---

## ⚠️ Disclaimer

This is an **unofficial, educational project** created for learning web development. It is not affiliated with, endorsed by, or connected to Tata Motors. All brand names, logos, car names and images are the property of their respective owners and are used here for demonstration purposes only.

The order form is a **front-end demo with no backend**. It does not send or store any data, so please **do not enter real personal information** (such as Aadhaar, PAN or phone numbers) into it.

---

## 🤝 Contributing

Suggestions, bug reports and improvements are very welcome, especially since this is a learning project.

```bash
# 1. Fork the repo, then create a branch
git checkout -b feature/amazing-idea

# 2. Make your changes and commit
git commit -m "Add amazing idea"

# 3. Push and open a Pull Request
git push origin feature/amazing-idea
```

Found a bug? [Open an issue](https://github.com/Yugcoder123/TATA-MOTORS/issues).

---

<div align="center">

### 👤 Author

**Yugcoder123** · [GitHub](https://github.com/Yugcoder123)

If this project made you smile, drop a ⭐. Every first project deserves one.

*Built with curiosity, a lot of refreshes, and a love for cars. 🏎️*

</div>
