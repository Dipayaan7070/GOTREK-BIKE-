# 🚲 GOTREK – Electric Bike Promotional Website

A modern, responsive **electric bike promotional website** designed for the GOTREK brand. The project focuses on creating an attractive product-focused landing page with responsive layouts, interactive sliders, promotional sections, product cards, a sale countdown, and customer testimonials.

The website is built using **HTML5, CSS3, and Vanilla JavaScript**, with Swiper.js and icon/font libraries loaded through CDN.

---

## 🌐 Project Overview

**GOTREK** is a frontend web design project created to showcase a modern electric bike brand and its products.

The website combines bold typography, product imagery, promotional banners, responsive layouts, sliders, and interactive UI elements to create a modern e-commerce-style experience.

### Main goals of the project

- Create a professional electric-bike brand website
- Build a modern and visually attractive landing page
- Create a responsive layout for desktop, tablet, and mobile devices
- Showcase multiple bike products and collections
- Add interactive sliders and navigation
- Create promotional and sale sections
- Practice advanced HTML and CSS layouts
- Implement interactive elements using Vanilla JavaScript

---

## ✨ Features

### 🏠 Responsive Header

- GOTREK logo
- Navigation menu
- Search box
- Shopping cart icon
- Cart item badge
- Responsive hamburger menu for smaller screens

### 🎯 Hero / Banner Section

- Full-screen promotional banner
- GOTREK electric bike presentation
- Product-focused typography
- Background graphics
- Promotional CTA button
- Automatic image/content slider
- Swiper navigation and pagination

### 🎁 Promotional Cards

Three promotional cards are displayed:

- Mountain bike discount
- Bike accessories promotion
- Premium riding gear

Each card includes a product image and collection CTA.

### 🚴 About GOTREK

The About section introduces the GOTREK brand and highlights:

- Eco-friendly transportation
- Electric vehicle technology
- Battery performance
- Quick charging
- City commuting
- Open-road riding

### 🛒 Bike Collection

The **"I Want a Bike"** section showcases multiple bike products with:

- Product images
- Product names
- Prices
- Wishlist icon
- Shopping cart icon
- Order Now button
- Swiper carousel

### ⚙️ Features Section

Highlights the advantages of GOTREK electric bikes, including:

- Zero emissions
- Regenerative braking
- Instant torque
- Low maintenance
- Eco-friendly transportation

### 📦 Featured Collections

The website contains several promotional collections, including:

- New 2025 Trek Collection
- Future Model
- Black Ride
- GOTREK Signature Ride

### 🔥 Summer Sale Countdown

A promotional sale section includes a live countdown displaying:

- Days
- Hours
- Minutes
- Seconds

The countdown is controlled using JavaScript.

### ⭐ Testimonials

A customer testimonial section contains:

- Customer reviews
- Star ratings
- Customer names
- GOTREK customer labels
- Testimonial navigation

### 📱 Responsive Design

The website contains multiple responsive breakpoints to adapt the layout for:

- Desktop
- Laptop
- Tablet
- Mobile
- Small mobile screens

The CSS includes support down to **320px screen width**.

---

## 🛠️ Technologies Used

### Frontend

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**

### Libraries & Resources

- **Swiper.js** – Product and hero sliders
- **Font Awesome** – Icons
- **Google Material Symbols** – UI icons
- **Google Fonts** – Typography

### Development Tools

- Visual Studio Code
- Git
- GitHub

---

## 📁 Project Structure

```text
GOTREK/
│
├── index.html
├── style.css
│
├── img/
│   ├── Aboutbikegrid.png
│   ├── AboutIntersect.png
│   ├── bannerbackground.png
│   ├── bannerbike.png
│   ├── bannerBIKEtext.png
│   ├── bannerorangebox.png
│   ├── bg-pattern.png
│   ├── cardimg1.png
│   ├── cardimg2.png
│   ├── cardimg3.png
│   ├── featursimg.png
│   ├── footerbackground.png
│   ├── footerimage.png
│   ├── ftbackgroundimg.png
│   ├── ftcollection1.png
│   ├── ftcollection2.png
│   ├── ftcollection3.png
│   ├── ftcollection4.png
│   ├── ftcollection5.png
│   ├── headerlogo.png
│   ├── iwantbike1.png
│   ├── iwantbike2.png
│   ├── iwantbike3.png
│   ├── salebg.png
│   ├── salebgtext.png
│   ├── salebike.png
│   └── Testimonial2.png
│
└── .vscode/
    └── settings.json
```

---

## 🚀 Getting Started

Since this is a static frontend project, no backend server or database is required.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gotrek-bike-website.git
```

### 2. Open the project

```bash
cd gotrek-bike-website
```

### 3. Run the website

Simply open:

```text
index.html
```

in your browser.

### Recommended

For development, use the **Live Server** extension in Visual Studio Code.

Right-click `index.html` and select:

```text
Open with Live Server
```

---

## 🎨 Design Highlights

The website uses a custom responsive layout rather than relying entirely on a CSS framework.

### Custom Container

The main content uses a maximum width of:

```css
.container {
    width: 100%;
    max-width: 1530px;
    margin: 0 auto;
}
```

This keeps the website content aligned across large desktop screens.

### Custom Grid

The project uses custom column classes such as:

```text
.col50
.col33
```

to create flexible two-column and three-column layouts.

### Responsive Breakpoints

The CSS contains multiple breakpoints for different screen sizes, including:

```text
1024px
991px
768px
600px
575px
480px
420px
380px
370px
320px
```

---

## ⚡ JavaScript Functionality

JavaScript is used for several interactive components.

### Mobile Navigation

The hamburger menu toggles the mobile navigation menu.

### Hero Slider

Swiper.js provides:

- Automatic slide rotation
- Navigation arrows
- Pagination
- Infinite looping
- 4-second autoplay

### Bike Product Slider

The bike collection uses Swiper.js with responsive slide counts.

Example:

```text
320px  → 1 product
480px  → 2 products
768px  → 3 products
1024px → 4 products
```

### Sale Countdown

JavaScript dynamically calculates the remaining time for the promotional sale.

### Testimonial Slider

A custom JavaScript slider is also implemented for customer testimonials.

---

## 📱 Responsive Design

The project was designed to work across different screen sizes.

| Device | Support |
|---|---|
| Desktop | ✅ |
| Laptop | ✅ |
| Tablet | ✅ |
| Mobile | ✅ |
| Small Mobile | ✅ |
| 320px screens | ✅ |

The layout adapts navigation, columns, typography, product sliders, images, and spacing according to screen width.

---

## 🧩 Current Project Scope

This project is currently a **frontend promotional/e-commerce-style website**.

The following features are currently visual/demo functionality:

- Search functionality
- Shopping cart processing
- Product ordering
- Wishlist storage
- Checkout
- User authentication
- Product database
- Payment processing
- Backend API

These can be added in future versions using technologies such as:

```text
Node.js
Express.js
MongoDB
REST API
Authentication
Payment Gateway
```

---

 🔮 Future Improvements

Possible improvements for future versions include:

- [ ] Add functional product search
- [ ] Add individual product pages
- [ ] Implement shopping cart functionality
- [ ] Add wishlist functionality
- [ ] Add checkout page
- [ ] Add user authentication
- [ ] Connect products to a backend API
- [ ] Add MongoDB database
- [ ] Add admin dashboard
- [ ] Add real product filtering
- [ ] Add payment gateway
- [ ] Add form validation
- [ ] Improve accessibility
- [ ] Optimize images for faster loading
- [ ] Deploy the website online

---

 📸 Project Sections

The website contains the following major sections:

```text
Header
   ↓
Hero / Banner
   ↓
Promotional Cards
   ↓
About GOTREK
   ↓
Bike Collection
   ↓
Features
   ↓
Featured Collections
   ↓
Summer Sale
   ↓
Testimonials
   ↓
Footer




 💻 Learning Outcomes

This project helped demonstrate practical experience with:

- Semantic HTML structure
- CSS Flexbox
- Responsive web design
- Custom CSS layouts
- CSS positioning
- Background image composition
- Typography and Google Fonts
- JavaScript DOM manipulation
- Event listeners
- Responsive navigation
- Swiper.js integration
- Product card design
- Carousel implementation
- Countdown timers
- Mobile-first considerations
- Git/GitHub project organization

---

## 👨‍💻 Author

**Dipayan Chowdhury**

Frontend Developer

### Skills demonstrated in this project

```text
HTML5
CSS3
JavaScript
Responsive Web Design
Swiper.js
Font Awesome
Material Symbols
Git
GitHub
```

---

## 📄 License

This project is intended primarily for **educational and portfolio purposes**.

The images and visual assets used in the project should be used only according to their applicable licenses or permissions.

---

## ⭐ Acknowledgement

Built as a frontend web development project to practice modern responsive website design and interactive user interfaces.

If you like the project, consider giving the repository a ⭐ on GitHub.
