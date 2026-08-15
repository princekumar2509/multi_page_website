# 🌐 NovaWeb – Multi-Page Responsive Website

A modern, responsive, and professional multi-page website built using **HTML5, CSS3, and JavaScript**.

This project demonstrates how to create multiple interconnected web pages with a consistent user interface, responsive layouts, interactive navigation, and a mobile-friendly hamburger menu.

---

## 📌 Project Overview

**NovaWeb** is a multi-page website developed as part of a web development project.

The website contains four main pages:

- 🏠 Home
- 👥 About
- 💼 Services
- 📩 Contact

Each page follows the same visual design and navigation structure, providing a consistent user experience across the website.

---

## 🎯 Objective

The objective of this project is to build a complete multi-page website that demonstrates:

- Responsive web design
- Navigation between multiple pages
- Consistent UI across pages
- Mobile-friendly layouts
- Interactive hamburger navigation
- Professional website structure
- CSS styling and animations

---

## ✨ Features

### 🏠 Home Page

- Attractive hero section
- Website introduction
- Call-to-action button
- Feature cards
- Responsive layout

### 👥 About Page

- Introduction about the organization
- Mission and purpose
- Responsive image section
- Consistent navigation

### 💼 Services Page

The website provides three sample services:

- 🌐 Web Development
- 🎨 UI/UX Design
- 📱 App Development

Each service is presented using an interactive card with hover effects.

### 📩 Contact Page

- Contact information
- Name field
- Email field
- Subject field
- Message field
- Submit button
- Responsive contact layout

### 📱 Responsive Design

The website automatically adapts to:

- Desktop
- Laptop
- Tablet
- Mobile devices

### ☰ Hamburger Menu

On smaller screens, the desktop navigation changes into a hamburger menu.

Users can click the menu icon to display:

- Home
- About
- Services
- Contact

### 🎨 UI Features

- Modern color scheme
- Hover animations
- Card shadows
- Responsive layouts
- Active navigation indicator
- Clean typography
- Consistent footer

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive design |
| JavaScript | Hamburger menu interaction |
| Google Fonts | Typography |
| Font Awesome | Navigation icons |

---

## 📁 Project Structure

```text
NovaWeb/
│
├── index.html
├── about.html
├── services.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   └── about.jpg
│
└── README.md
```

---

## 🚀 How to Run the Project

### Method 1 – Open Directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The website will open in your browser.

---

### Method 2 – Using VS Code Live Server

1. Open the project in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. The website will open in your browser.

---

## 📱 How to Test on Mobile

### Using Browser Developer Tools

1. Open the website in Google Chrome.
2. Press `F12`.
3. Click the **Toggle Device Toolbar** icon.
4. Select a mobile device.
5. Refresh the page.
6. Test the hamburger menu and page layouts.

### Using a Real Mobile Device

If your computer and phone are connected to the same Wi-Fi network:

1. Start Live Server.
2. Find your computer's IPv4 address using:

```bash
ipconfig
```

3. Find the IPv4 address, for example:

```text
192.168.1.10
```

4. On your phone, open:

```text
http://192.168.1.10:5500
```

> The port number may be different depending on your Live Server configuration.

---

## 🧭 Website Navigation

The website uses HTML links to connect all pages:

```text
Home
 ↓
About
 ↓
Services
 ↓
Contact
```

Users can move between pages using the navigation bar.

---

## ☰ Mobile Navigation

The hamburger menu is controlled using JavaScript.

The main functionality is:

```javascript
const menu = document.getElementById("mobile-menu");
const nav = document.getElementById("nav-links");

menu.addEventListener("click", () => {
    nav.classList.toggle("active");
});
```

When the user clicks the menu icon, the navigation links are displayed or hidden.

---

## 🎨 Design

The website uses a modern blue-based color palette:

```text
Primary:    #2563EB
Dark:       #1E293B
Accent:     #F59E0B
Background: #F8FAFC
```

The website uses **Poppins** for clean and modern typography.

---

## 📱 Responsive Breakpoint

The website uses a CSS media query for smaller devices:

```css
@media (max-width: 768px) {
    /* Mobile styles */
}
```

At screen widths below 768px:

- Navigation changes to a hamburger menu
- Cards stack vertically
- Content becomes mobile-friendly
- Contact sections stack vertically
- Hero text becomes smaller

---

## 🎓 Learning Outcomes

Through this project, I learned:

- How to create multiple HTML pages
- How to connect pages using navigation links
- How to use external CSS
- How to create responsive layouts
- How to use Flexbox
- How to use CSS media queries
- How to create hover effects
- How to implement a hamburger menu
- How to use JavaScript for interactive elements
- How to organize a web project professionally

---

## 🔮 Future Improvements

The project can be further improved by adding:

- 🌙 Dark mode
- 📧 Functional contact form
- 🗺️ Google Maps integration
- 🔐 User authentication
- 💾 Backend database
- ✨ More animations
- 📊 Admin dashboard
- 🌐 Deployment with a custom domain

---

## 👨‍💻 Author

**Prince Kumar**

Computer Science Student

---

## 📄 License

This project is created for **educational and academic purposes**.

---

⭐ If you like this project, consider giving the repository a **star** on GitHub.