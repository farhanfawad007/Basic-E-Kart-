🛍️ E-Cart E-Commerce Platform

A premium, fully responsive front-end e-commerce experience for stylish and fashionable bags.

✨ Features •
🔐 Live Demo Auth •
🚀 Quick Start •
📂 Structure

✨ Key Features

Feature

Description

🎨 Modern Glassmorphism UI

Features frosted-glass effects, smooth gradient backgrounds (#e2852e), and beautiful hover animations.

📱 Fully Responsive Design

CSS Grid and Flexbox implementation ensures the store looks perfect on desktops, tablets, and mobile devices.

🔒 Client-Side Auth System

A fully functional dummy login system using localStorage. Keeps users logged in across page reloads.

⚡ Dynamic Navbar

Navigation updates in real-time to show the user's username and a logout button when authenticated.

🛍️ Interactive Product Grid

Beautifully styled product cards displaying premium bags with hover-scaling and shadow effects.

🔐 Live Demo Authentication

Want to test the login modal and see the dynamic navbar in action? Use the following hardcoded demo credentials:

Email: farhanfawad007@gmail.com

Password: 1234567

Note: Upon successful login, the UI will greet you, hide the login button, and reveal your session controls.

🚀 Quick Start

Getting this project running locally takes less than a minute.

Clone the repository:

git clone https://github.com/yourusername/e-cart.git


Navigate to the directory:

cd e-cart


Run the project:
Simply double-click the index.html file to open it in your default web browser. No local server or build steps are required!

📂 Project Structure

📦 E-Cart
 ┣ 📜 index.html      # Landing page featuring the hero section
 ┣ 📜 products.html   # Storefront displaying the responsive bag grid
 ┣ 📜 style.css       # Core stylesheet containing all glassmorphism & animations
 ┗ 📜 auth.js         # Vanilla JS logic handling modals, login, and LocalStorage


💻 Technical Details

backdrop-filter: blur(10px) for modern glassmorphism components.

Sticky navigation bar (position: sticky) for easy access while scrolling.

Responsive grid utilizing grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)).

CSS Keyframes for smooth modal slide-down and hero section fade-in animations.

Prevents default form submissions for custom validation.

Uses localStorage.setItem() and getItem() to persist user sessions.

Dynamically toggles CSS display properties to show/hide the login modal and update navbar UI elements.
