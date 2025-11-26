# 🎨 Craftivo - Modern Portfolio Template

<div align="center">

![Craftivo Banner](assets/img/profile/profile-bg-5.webp)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-purple.svg)](https://getbootstrap.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**A beautiful, responsive portfolio website template for developers, designers, and creative professionals.**

[Live Demo](#) • [Report Bug](../../issues) • [Request Feature](../../issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## 🎯 About The Project

Craftivo is a sleek and modern portfolio template designed for professionals who want to showcase their work, skills, and experience in an elegant way. Built with Bootstrap 5 and enhanced with smooth animations using AOS (Animate On Scroll), this template provides everything you need to create a stunning online presence.

### Why Craftivo?

- **Modern Design**: Clean, contemporary aesthetics that make your portfolio stand out
- **Fully Responsive**: Looks great on all devices - from mobile phones to desktop monitors
- **Easy to Customize**: Well-organized code structure makes modifications a breeze
- **Performance Optimized**: Fast loading times for better user experience
- **SEO Friendly**: Built with search engine optimization in mind

---

## ✨ Features

### Core Features
- 📱 **Fully Responsive Design** - Adapts seamlessly to all screen sizes
- 🎨 **Modern UI/UX** - Clean and professional interface
- 🌙 **Dark Mode Support** - Toggle between light and dark themes
- ⚡ **Smooth Animations** - Powered by AOS (Animate On Scroll)
- 🔤 **Typed.js Integration** - Dynamic typing effects in the hero section
- 🖼️ **Portfolio Filtering** - Isotope-powered portfolio with category filters
- 📧 **Contact Form** - Ready-to-use PHP contact form
- 🔝 **Scroll to Top** - Convenient navigation button

### Sections Included
- **Hero Section** - Eye-catching introduction with animated text
- **About Me** - Profile card with stats, skills, and social links
- **Resume/Experience** - Professional timeline layout
- **Services** - Showcase your offerings with beautiful cards
- **Portfolio** - Filterable gallery of your work
- **Testimonials** - Client reviews carousel
- **Contact** - Contact information and working form

### Additional Pages
- `index.html` - Main homepage
- `portfolio-details.html` - Individual project showcase
- `service-details.html` - Detailed service description
- `privacy.html` - Privacy policy page
- `terms.html` - Terms of service page
- `404.html` - Custom error page
- `starter-page.html` - Blank template for new pages

---

## 🛠️ Built With

This project uses the following technologies and libraries:

| Technology | Description |
|------------|-------------|
| [Bootstrap 5](https://getbootstrap.com/) | CSS Framework |
| [AOS](https://michalsnik.github.io/aos/) | Animate On Scroll Library |
| [Typed.js](https://mattboldt.com/demos/typed-js/) | Typing Animation |
| [GLightbox](https://biati-digital.github.io/glightbox/) | Lightbox Plugin |
| [Isotope](https://isotope.metafizzy.co/) | Portfolio Filtering |
| [Swiper](https://swiperjs.com/) | Touch Slider |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | Icon Library |

---

## 🚀 Getting Started

### Prerequisites

No special prerequisites are needed! Just a web browser and a code editor.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/lewiii254/Merlin-Class-Collaboration-Project.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Merlin-Class-Collaboration-Project
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server like VS Code's Live Server extension

### Using a Local Server (Recommended)

For the best development experience, use a local server:

**Using VS Code Live Server:**
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

**Using Node.js:**
```bash
# Install http-server globally
npm install -g http-server

# Run the server
http-server

# Then open http://localhost:8080 in your browser
```

---

## 📁 Project Structure

```
Merlin-Class-Collaboration-Project/
├── assets/
│   ├── css/
│   │   └── main.css          # Main stylesheet
│   ├── img/
│   │   ├── portfolio/        # Portfolio images
│   │   ├── profile/          # Profile images
│   │   └── ...               # Other images
│   ├── js/
│   │   └── main.js           # Main JavaScript file
│   ├── scss/                  # SCSS source files
│   └── vendor/                # Third-party libraries
├── forms/
│   ├── contact.php           # Contact form handler
│   └── Readme.txt            # Form documentation
├── index.html                 # Main homepage
├── portfolio-details.html    # Portfolio detail page
├── service-details.html      # Service detail page
├── privacy.html              # Privacy policy
├── terms.html                # Terms of service
├── 404.html                  # Error page
├── starter-page.html         # Blank template
├── README.md                  # This file
├── CONTRIBUTING.md            # Contribution guidelines
└── Readme.txt                # Original template readme
```

---

## 🎨 Customization

### Changing Content

1. **Personal Information**: Edit `index.html` to update your name, bio, and contact details
2. **Profile Image**: Replace images in `assets/img/profile/`
3. **Portfolio Items**: Update portfolio images in `assets/img/portfolio/`
4. **Social Links**: Search for `social-links` class and update the `href` attributes

### Styling Changes

1. **Colors**: Modify CSS custom properties in `assets/css/main.css`
2. **Fonts**: Update font imports in the `<head>` section of HTML files
3. **Advanced Styling**: Edit SCSS files in `assets/scss/` and compile

### Adding New Sections

1. Copy an existing section from `index.html`
2. Modify the content and IDs
3. Add navigation link in the `<nav>` element
4. Add corresponding styles if needed

---

## 🤝 Contributing

We welcome contributions from the community! This is an open-source project, and your input is valuable.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

### Types of Contributions

- 🐛 **Bug Fixes**: Found a bug? Help us squash it!
- ✨ **New Features**: Have an idea? We'd love to hear it!
- 📝 **Documentation**: Help improve our docs
- 🎨 **Design**: Suggest UI/UX improvements
- 🌐 **Translations**: Help localize the template

---

## 📄 License

This template is based on the Craftivo Bootstrap Template by BootstrapMade.

**License**: https://bootstrapmade.com/license/

Please note:
- The footer credits must remain intact unless you purchase the pro version
- Commercial use requires proper licensing
- See the original template license for full details

---

## 📞 Contact

**Cyrus Maundu** - Project Maintainer

- 📍 Location: Nairobi, Kenya
- 📱 Phone: +254 701760976
- 📧 Email: mweru@gmail.com

Project Link: [https://github.com/lewiii254/Merlin-Class-Collaboration-Project](https://github.com/lewiii254/Merlin-Class-Collaboration-Project)

---

## 🙏 Acknowledgments

- [BootstrapMade](https://bootstrapmade.com/) - Original template design
- [Bootstrap](https://getbootstrap.com/) - CSS Framework
- [Bootstrap Icons](https://icons.getbootstrap.com/) - Icon library
- [Font Awesome](https://fontawesome.com/) - Additional icons
- [Google Fonts](https://fonts.google.com/) - Typography
- All contributors who help improve this project!

---

<div align="center">

**⭐ Star this repo if you find it helpful! ⭐**

Made with ❤️ by the Merlin Class Collaboration Team

</div>
