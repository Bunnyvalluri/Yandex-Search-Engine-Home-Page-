# Yandex Search Engine Home Page Replica

A front-end replication of the Yandex homepage built using pure HTML, CSS Flexbox/Grid layouts, and vanilla JavaScript for interactive elements. This project serves as a comprehensive practice of advanced responsive design, CSS variables, and clean layouts.

## 🚀 Live Demo & Repository

- **Netlify Live Demo:** [yandex-20.netlify.app](https://yandex-20.netlify.app)
- **GitHub Pages Demo:** [bunnyvalluri.github.io/Yandex-Search-Engine-Home-Page-](https://bunnyvalluri.github.io/Yandex-Search-Engine-Home-Page-/)
- **GitHub Repository:** [Bunnyvalluri/Yandex-Search-Engine-Home-Page-](https://github.com/Bunnyvalluri/Yandex-Search-Engine-Home-Page-)

---

## 🌟 Key Features

### 1. Navigation & Header
- **Top Services Bar:** Links to Mail, Disk, Music, News, Travel, Market, and a dropdown "More" link.
- **Dynamic Clock & Date:** Shows real-time updating time and date (refreshes automatically every 10 seconds).
- **Weather pill:** High-quality inline SVG sun icon displaying temperature.
- **Profile Access Button:** A modern circular profile avatar button with hover scale effects, active scale feedback, and red glow drop shadows.

### 2. Main Search & Brand Logo
- **Official SVG Wordmark:** Embeds the official Yandex vector wordmark paths, preventing baseline bottom-clipping and scaling cleanly to any screen resolution.
- **Enhanced Search Bar:**
  - Integrated magnifying glass, microphone, and camera buttons.
  - Interactive mic button triggering a listening pulsate animation when clicked.
- **Search Suggestions Dropdown:**
  - A responsive list of search recommendations that opens when the input is focused.
  - Full keyboard navigation support (up/down arrow keys to traverse suggestions, Enter to submit, Escape to close).

### 3. Services Grid
- Grid layout showcasing 11 primary services (Images, Video, Maps, Translate, News, Music, etc.) and an "All services" grid icon.
- Each service features a unique, modern linear-gradient wrap background and uses high-resolution Font Awesome vector icons.
- Built-in scale click translations and shadow expansions on hover.

### 4. Centered News Feed
- Single-column centered layout aligned with the main search bar, dynamically rendering news cards.
- **Interactive News Categories:** Clicking news tabs (All, World, Tech, Sports, Business) instantly filters and renders related articles.
- **Staggered Animations:** Loaded articles animate smoothly into view with an elegant, staggered fade-in (`fadeInUp`) transition.
- **Dynamic Pagination:** The "Show more news" button loads additional articles incrementally (3 at a time) specific to the selected category.
- **Real Visuals:** Custom AI-generated news cover photos matching each topic (e.g., climate accord, deep ocean expeditions, bullet trains, quantum computing, athletics events, tennis, green energy, autonomous delivery fleets).

### 5. Multi-Language Footer
- Clean bottom row showing copyright details, support links, and a stylized globe icon next to a custom language selector.

---

## 📱 Responsive Layout System

The site implements custom media query brackets to scale cleanly across all screens:

| Device Bracket | Width Range | Layout Configurations |
| :--- | :--- | :--- |
| **Large Desktop** | `1441px+` | Content container width expands to `860px`; logo scales to `230px` width. |
| **Desktop** | `1025px - 1440px` | Standard Yandex centered layout (`760px` container). |
| **Small Laptop** | `769px - 1024px` | 6-column grid maintained; padding and margin sizing condensed. |
| **Tablet** | `481px - 768px` | Services grid converts to `4` columns; responsive padding scales down. |
| **Large Mobile** | `376px - 480px` | Search bar items stack vertically, top links hide, grid turns to `3` columns, thumbnails reduce to `80x60px`. |
| **Small Mobile** | `320px - 375px` | Sizing compressed further; service icon containers scale down to `42px`, and news cards scale to `70px` to fit. |

---

## 🛠️ Technologies Used

- **HTML5:** Semantic architecture (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`).
- **CSS3:** Custom properties (design tokens), Flexbox for alignments, CSS Grid for the services panel, animations, and keyframes.
- **JavaScript:** Vanilla DOM manipulation for the clock, suggestions keyboard controls, tab active toggling, and input focuses.
- **Font Awesome 6.5.2:** Vector icons for all services.
- **Google Fonts:** Inter typography.

---

## 📂 Project Structure

```
├── images/
│   ├── news_ai_summit.png
│   ├── news_athletics_record.png
│   ├── news_autonomous_vans.png
│   ├── news_bullet_train.png
│   ├── news_climate_accord.png
│   ├── news_deep_ocean.png
│   ├── news_football_trophy.png
│   ├── news_green_energy.png
│   ├── news_phone_battery.png
│   ├── news_quantum_computing.png
│   ├── news_space_galaxy.png
│   ├── news_stock_market.png
│   └── news_tennis_victory.png
├── index.html
├── style.css
└── README.md
```

---

## 💻 Running the Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Bunnyvalluri/Yandex-Search-Engine-Home-Page-.git
   ```
2. Navigate into the folder:
   ```bash
   cd Yandex-Search-Engine-Home-Page-
   ```
3. Open `index.html` directly in your browser or run it using a local development server extension (e.g., Live Server in VS Code).
