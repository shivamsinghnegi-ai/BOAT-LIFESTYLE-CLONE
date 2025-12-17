# boAt Lifestyle - E-commerce Website Clone

A modern, responsive e-commerce website clone for boAt lifestyle products, featuring a festive sale theme with product showcases, carousels, and a clean user interface.

**[🔗 View Live Site](https://boatclone1.netlify.app/)**

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Key Components](#key-components)
- [Deployment](#deployment)
- [Screenshots](#screenshots)

## 🎯 Overview

This project is a single-page e-commerce website clone inspired by boAt lifestyle's festive sale page. It showcases various audio products including True Wireless Earbuds (TWS), Smartwatches, Speakers, Earphones, and Accessories with attractive deals and discounts.

## ✨ Features

### Navigation & Header
- **Responsive Header**: Logo and navigation menu with hover effects
- **Search Functionality**: Search bar with icon
- **User Icons**: User account and shopping bag icons
- **Interactive Navigation**: Hover effects with underline animations

### Image Carousel
- **Auto-sliding Carousel**: Automatically transitions through 5 promotional banners every 3 seconds
- **Full-screen Display**: Full viewport width and height carousel
- **Smooth Transitions**: CSS transitions for seamless slide changes

### Product Sections
The website features multiple product showcase sections:

1. **Best Festive Deals**
   - Category tabs (All Deals, True Wireless Earbuds, Smartwatches, Speakers, Earphones)
   - Product cards with badges, images, and pricing

2. **Choose Your Offers**
   - Discount coupon tabs (Extra ₹500 off, ₹400 off, ₹300 off, ₹100 off)
   - Featured products with special offers

3. **Top TWS Offers**
   - True Wireless Earbuds collection
   - Highlighted features and discounts

4. **Exclusive Home Audio Steals**
   - Speakers and home audio products
   - Product specifications and pricing

5. **Smartwatches At Best Prices**
   - Smartwatch collection with BT Calling features
   - Modern design showcase

6. **Best Deals on Accessories**
   - Power banks and charging accessories
   - Battery capacity and charging specifications

### Product Cards
Each product card includes:
- **Status Badges**: "New Launch", "Recently Restocked", "Engraving Available"
- **Product Images**: High-quality product photos
- **Feature Tags**: Playback hours, battery capacity, special features
- **Pricing**: Current price, original price (strikethrough), discount percentage
- **Hover Effects**: Enhanced user interaction

### Footer
- **Email Subscription**: Newsletter signup form
- **Organized Links**: Shop, Help, and Company sections
- **Brand Information**: boAt logo and branding

## 🛠 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, transitions, and animations
- **JavaScript**: Vanilla JS for carousel functionality
- **Netlify**: Deployment configuration included

## 📁 Project Structure

```
boat lifestyle/
│
├── assets/                    # Product images and logos
│   ├── boAt_logo_small_*.png
│   ├── Desktop_Festive_*.png  # Carousel banners
│   ├── AD_*.png              # Airdopes products
│   ├── Rockerz_*.png         # Headphone products
│   ├── Stone_*.png           # Speaker products
│   ├── Wave_*.png            # Smartwatch products
│   └── ...                   # Other product images
│
├── index.html                # Main HTML file
├── styles.css                # All styling
├── script.js                 # JavaScript functionality (minimal)
├── netlify.toml             # Netlify deployment config
└── README.md                # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "boat lifestyle"
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using VS Code Live Server extension
     # Right-click index.html > Open with Live Server
     ```

3. **View the website**
   - Navigate to `http://localhost:8000` (or your chosen port)
   - The website should load with all features working

## 🎨 Key Components

### Carousel Implementation
The carousel uses vanilla JavaScript with automatic sliding:
- **Interval**: 3 seconds between slides
- **Transition**: Smooth CSS transform animations
- **Loop**: Infinite loop through all slides

### Product Card Design
- **Responsive Layout**: Flexbox-based horizontal scrolling
- **Visual Hierarchy**: Badges, tags, and pricing clearly displayed
- **Color Scheme**: Orange accents (#ff6a00) for highlights, green for discounts

### Styling Highlights
- **Modern UI**: Clean, minimalist design
- **Smooth Animations**: Hover effects and transitions
- **Color Palette**: 
  - Primary: Orange (#ff6a00)
  - Accent: Gold (#ffd700) for tags
  - Background: Light blue (#e8f0f8) for footer

## 🌐 Deployment

### Netlify Deployment
The project includes a `netlify.toml` configuration file for easy deployment:

1. **Push to Git repository**
2. **Connect to Netlify**
3. **Deploy**: Netlify will automatically detect the configuration

The `netlify.toml` includes:
- SPA redirect rules (all routes redirect to index.html)

### Alternative Deployment Options
- **GitHub Pages**: Simple static site hosting
- **Vercel**: Modern deployment platform
- **Any static hosting service**: The project is purely static files

## 📱 Responsive Design

The website is designed with responsiveness in mind:
- **Flexible Layouts**: Uses flexbox for adaptable components
- **Viewport Units**: Carousel uses 100vw/100vh for full-screen display
- **Scrollable Sections**: Horizontal scrolling for product carousels

## 🔧 Customization

### Adding New Products
1. Add product image to `assets/` folder
2. Create a new card in the appropriate section:
   ```html
   <div class="card">
       <div class="badge">New Launch</div>
       <img src="./assets/product-image.png" alt="Product Name">
       <div class="product-info">
           <div class="tag">Feature Tag</div>
           <h3>Product Name</h3>
           <p>₹Price <span class="original-price">₹Original</span> <span class="discount">X% off</span></p>
       </div>
   </div>
   ```

### Modifying Carousel
- Change slide interval in `index.html` (line 68): `setInterval(..., 3000)`
- Add/remove slides by adding/removing `<li class="carousel-slide">` elements

### Styling Changes
- Primary color: Modify `#ff6a00` in `styles.css`
- Font family: Change `font-family` in body selector
- Spacing: Adjust padding and margin values

## 📝 Notes

- This is a **frontend-only** project (no backend functionality)
- Product links and search functionality are placeholders
- Images are stored locally in the `assets/` folder
- The design is optimized for desktop viewing

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements:
- Responsive design enhancements
- Additional features
- Performance optimizations
- Bug fixes

## 📄 License

This project is created for educational purposes as a clone/recreation of boAt's website design.

## 👨‍💻 Author

Created as part of the Diwali Vacation Project.

---

**Note**: This is a clone/recreation project for educational purposes. All product names, logos, and images are property of their respective owners (boAt Lifestyle).
