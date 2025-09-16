# 🌗 Light-Dark Mode Toggle Project

A simple and interactive project that allows users to switch between **Dark Mode** and **Light Mode** dynamically.  
The theme selection is stored using **localStorage**, so your preferred mode is saved even after reloading or reopening the browser.

---

## 🚀 Features

- ✅ **Dark/Light Mode Toggle** – Smooth switching between dark and light UI.  
- ✅ **Dynamic Image Loading** – Images change according to the selected mode (`dark` / `light`).  
- ✅ **Persistent Theme** – Saves your theme preference in **localStorage** so it remembers your choice.  
- ✅ **Font Awesome Icons** – Toggle button updates icon between ☀️ Sun (light) and 🌙 Moon (dark).  
- ✅ **Custom Styling** – Nav and Textbox adapt background colors based on theme.

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**  
- **Font Awesome Icons**

---

## 📂 Project Setup

1. Clone the repository:  
   ```bash
   git clone <your-repo-link>
Open the project folder and run in your browser (no build tools required).

🔗 Links
GitHub Repo: Your Repo Link

Live Demo: https://devsenlightdarkmode.netlify.app

---

### 📸 Screenshots

🌞 Light Mode
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/2348a5b1-0b7f-40ed-8118-7b4c1f930c20" />


🌙 Dark Mode
<img width="1440" height="900" alt="image" src="https://github.com/user-attachments/assets/2d88d347-c122-40e7-a56f-1ac4a5077d36" />


📌 Main Functions Explained
Local Storage Handling

js
Copy code
localStorage.setItem('theme', 'dark'); // Save preference
const currentTheme = localStorage.getItem('theme'); // Load preference
Dynamic Theme Switch

js
Copy code
toggleSwitch.addEventListener('change', switchTheme);
Dynamic Image Update

js
Copy code
function imageMode(color){
    image1.src = `img/undraw_proud_coder_${color}.svg`;
}
✨ Built with pure JavaScript – no frameworks, no dependencies.
