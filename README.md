# 🛒 Amazon Clone

A pixel-perfect front-end clone of **Amazon.com** built using only **HTML** and **CSS**. This project replicates Amazon's homepage layout including the navigation bar, search functionality, hero banner, product category cards, and a complete multi-panel footer — all without any JavaScript! 🎨

## 🚀 Live Demo

🔗 [amazon-clone-rust-gamma.vercel.app](https://amazon-clone-rust-gamma.vercel.app/)

<!-- Add a screenshot of your app here -->
<!-- ![Amazon Clone Screenshot](./Images/screenshot.png) -->

## ✨ Features

### 🔝 Navigation Bar
- **Amazon Logo** — Custom logo with background image styling
- **Delivery Location** — "Deliver to India" with location icon
- **Search Bar** — Category dropdown selector + search input + search icon
- **Account & Lists** — "Hello, sign in" with Account & Lists
- **Returns & Orders** — Quick access to returns section
- **Shopping Cart** — Cart icon with label

### 📋 Sub-Navigation Panel
- **Hamburger Menu** — "All" categories button
- **Quick Links** — Today's Deals, Customer Service, Registry, Gift Cards, Sell
- **Deals Banner** — "Shop Deals in Electronics" promotional link

### 🖼️ Hero Section
- **Full-Width Banner** — Large background hero image
- **Redirect Message** — Amazon India redirect notification bar

### 🛍️ Product Categories (8 Cards)
| Category | Image |
|----------|-------|
| 🏥 Health & Personal Care | healthcare.jpg |
| 💄 Beauty Products | beauty.jpg |
| 📚 Books | book.jpg |
| 🧹 Home Cleaner | homecleaner.jpg |
| 👗 Fashion & Cloths | cloth.jpg |
| 🎮 Gaming | gaming.jpg |
| 💪 Health | health.jpg |
| 🏠 Home Decoration | home.jpg |

### 🦶 Footer (4 Panels)
- **Panel 1** — "Back to Top" button
- **Panel 2** — Multi-column links: Get to Know Us, Connect with Us, Make Money with Us, Let Us Help You
- **Panel 3** — Amazon logo
- **Panel 4** — Conditions of Use, Privacy Notice, Ads Privacy, Copyright

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Page structure, semantic markup, navigation, product cards, footer |
| **CSS3** | Flexbox layout, background images, hover effects, color theming |
| **Font Awesome 6** | Icons (search, location, cart, hamburger menu) |

## 📊 Language Composition

![HTML](https://img.shields.io/badge/HTML-64.6%25-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-35.4%25-1572B6?style=flat-square&logo=css3&logoColor=white)

## 🎨 Color Palette

| Element | Color | Hex |
|---------|-------|-----|
| Navbar | Dark Black | `#0f1111` |
| Sub-nav Panel | Dark Blue-Gray | `#222f3d` |
| Shop Section BG | Light Gray | `#e2e7e6` |
| Footer Panel 1 | Slate Blue | `#37475a` |
| Footer Panel 2 & 3 | Dark Blue-Gray | `#222f3d` |
| Footer Panel 4 | Dark Black | `#0f1111` |
| Links | Amazon Teal | `#007185` |
| Search Hover | Orange | `orange` |

## 📂 Project Structure

```
Amazon-Clone/
├── Images/                          # All images and assets
│   ├── amzon_logo-removebg-preview.png   # Navbar Amazon logo
│   ├── amzlogo.png                       # Footer Amazon logo
│   ├── amzfavicon.png                    # Browser favicon
│   ├── hero img.jpg                      # Hero banner background
│   ├── healthcare.jpg                    # Health & Personal Care card
│   ├── beauty.jpg                        # Beauty Products card
│   ├── book.jpg                          # Books card
│   ├── homecleaner.jpg                   # Home Cleaner card
│   ├── cloth.jpg                         # Fashion & Cloths card
│   ├── gaming.jpg                        # Gaming card
│   ├── health.jpg                        # Health card
│   └── home.jpg                          # Home Decoration card
├── index.html                       # Main HTML page
├── style.css                        # All styles and layout
└── README.md                        # Project documentation
```

## 🧠 CSS Techniques Used

- **Flexbox** — Used extensively for navbar, panels, cards, and footer layouts
- **Flex Wrap** — Product cards wrap responsively in rows of 4
- **Background Images** — Hero section and product cards use `background-image` with `background-size: cover`
- **Hover Effects** — Border highlights on navbar items, orange border on search bar
- **Box Model** — Precise spacing with margins, padding, and borders
- **Custom Favicon** — Amazon-styled browser tab icon

## 🏁 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shobharam07/Amazon-Clone.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd Amazon-Clone
   ```
3. **Open in browser**
   ```bash
   open index.html
   ```
   Or simply open `index.html` in your preferred browser.

## 🙌 Contributing

Contributions, issues, and feature requests are welcome! Ideas for improvement:
- 📱 Add full responsive design for mobile/tablet
- 🔍 Implement working search functionality with JavaScript
- 🛒 Add a cart page
- 📄 Create additional pages (product details, login, checkout)
- 🎠 Add a hero image carousel/slider

## 📄 License

This project is open source and available for personal and educational use.

---

⭐ **If you found this project helpful, give it a star!**
