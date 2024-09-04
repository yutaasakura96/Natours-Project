# 🌍 Natours - Exciting Tours for Adventurous People

**Natours** is a fictional tour company website designed to inspire people to explore the natural world through exciting adventures. This project is built using advanced **SCSS** techniques, showcasing features like **animations**, **color management**, **responsive design** with **Sass mixins**, and modern web design practices.

![Screenshot 2024-09-04 at 14 47 22](https://github.com/user-attachments/assets/1ffd68ef-9383-4d16-bea6-baf662eb6192)

## Live Demo

Check out the live version of **Natours** here: <a href="https://natoursproject-yasakura.netlify.app/" target="_blank">Natours Live Demo</a>

## 🎯 Project Overview

This project was developed as part of the **Advanced CSS and Sass** course by **Jonas Schmedtmann**. It demonstrates how **SCSS** can be leveraged for creating clean, maintainable, and scalable CSS. The project features various components such as a popup modal, animations, and a responsive design without relying on **Flexbox** or **CSS Grid**.

## 🌟 Features

### 📱 Responsive Design with Sass Mixins
- Fully responsive layout using custom **Sass media query mixins**.
- Adaptive font sizes and padding using the **`respond`** mixin for various breakpoints:

### 🎥 Background Video Integration
- A beautiful **background video** on the "Stories" section that adds depth and context to the user experience. The **`object-fit`** property ensures the video covers the area without distorting.

### 🛠 Popup Modal with Smooth Transitions
- A **popup modal** opens when the user interacts with the "Book Now" button. This modal utilizes **animations**, **blur filters**, and **transform transitions** for a sleek, polished effect.

### 🖼️ Image Composition with Hover Animations
- Dynamic **image compositions** using **absolute positioning** with hover effects. The images respond with **scale** and **outline transitions**, creating a smooth and interactive gallery.

### 📑 Animated Booking Form
- An engaging **booking form** with custom radio buttons and input transitions. Labels move and inputs highlight when focused, providing real-time feedback and smooth visual cues.

### 🛍️ Interactive 3D Flip Cards
- Custom **3D flip cards** show key tour information. Each card flips when hovered, revealing more details such as pricing, duration, and difficulty.

### 🔍 Scroll and Hover Animations
- **Smooth animations** on various elements like buttons and headings using CSS **keyframes** for an immersive experience.

## 💻 Tech Stack

- **HTML5**: Semantic and accessible markup.
- **SCSS**: Modular styles using **BEM** and **Sass** with variables, mixins, and animations.
- **JavaScript**: Light interactivity and smooth scrolling for a seamless user experience.

## 🛠️ Key SCSS Features

### Colors and Font Management with Sass Variables

- All colors and fonts are managed through **Sass variables**, ensuring consistency across the site and enabling easy future updates.

### Media Queries with Mixin

- Responsive design is handled by the **`respond`** mixin, which allows for easy adjustment of styles at different breakpoints:

### Animations

- Multiple CSS animations are applied to various components to add interactivity, such as elements sliding into view on scroll or on hover. Example animation:

## 🚀 Getting Started

### Prerequisites

To run this project locally, you need:

- **Sass** installed globally.
- A modern browser that supports **CSS animations**, **Sass**, and **backdrop filters**.
- A code editor like **VSCode**.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/natours-project.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd natours-project
   ```

3. **Install Sass (if not installed):**
   ```bash
   npm install -g sass
   ```

4. **Compile SCSS to CSS:**
   Run the following command to watch for changes and compile SCSS into CSS:
   ```bash
   sass --watch sass/main.scss css/style.css
   ```

5. **Open `index.html` in your browser:**
   You can open the `index.html` file directly in your browser to view the project.

## 📄 License

This project is licensed under the **MIT License**.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch.
3. Submit a pull request for review.

---

Developed by **Yuta Asakura** as part of the **Advanced CSS and Sass** course by **Jonas Schmedtmann**. This project emphasizes **BEM** conventions and **SCSS** for scalable, maintainable, and visually engaging web design.
