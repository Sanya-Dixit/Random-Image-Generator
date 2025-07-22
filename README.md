# 📸 Random Image Feed

**Random Image Feed** is a simple, responsive web application that displays a gallery of randomly sized images using the Unsplash Source API. This lightweight project is built using HTML, CSS, and Vanilla JavaScript — perfect for beginners looking to practice DOM manipulation and API integration.

---

## 🚀 Features

- Dynamically loads a grid of random images from Unsplash
- Generates random image sizes for a unique layout
- Fully responsive and mobile-friendly design
- Clean and minimal UI

---

## 🛠️ Tech Stack

- **HTML5** — Page structure
- **CSS3** — Styling and layout
- **JavaScript (Vanilla)** — Logic and image generation
- **[Unsplash Source API](https://source.unsplash.com/)** — Random image source

---

## 📁 File Structure
📦 random-image-feed/
├── index.html # Main HTML structure
├── style.css # Styling and layout
└── script.js # Image fetching and DOM manipulation

---

## 📷 How It Works

1. On page load, the JavaScript file:
   - Selects the container.
   - Loops through 15 iterations (5 rows × 3 images each).
   - Creates image elements with random sizes (300–309px).
   - Appends each image with a unique Unsplash URL.

2. The images are fetched from:  
   `https://source.unsplash.com/random/{width}x{height}`

---

## 🖥️ Getting Started

### 🔧 Requirements

- A modern web browser (Chrome, Firefox, Edge, Safari)

### ⚙️ Steps to Run Locally

1. **Clone the repository:**

git clone https://github.com/your-username/random-image-feed.git
cd random-image-feed
Open index.html in your browser
(You can simply double-click the file or use Live Server in VS Code)

🌐 Live Demo
You can deploy it on GitHub Pages, Netlify, or Vercel for free.
Example deployment on GitHub Pages:
https://your-username.github.io/random-image-feed/
📸 Preview

📄 License
This project is open-source and free to use under the MIT License.

🙌 Acknowledgements
Unsplash Source API

---
