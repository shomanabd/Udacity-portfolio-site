# Portfolio Website

A clean, responsive portfolio website showcasing front-end development projects and skills. Built with modern web technologies and featuring smooth animations and a professional design.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging CSS animations including fade-in, slide-up, and slide-down effects
- **Modern UI**: Clean, professional design with a consistent color scheme
- **Interactive Elements**: Hover effects and smooth transitions
- **Contact Form**: Functional contact form for inquiries
- **Project Showcase**: Dedicated section highlighting key projects
- **About Section**: Personal introduction with professional photo

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **SCSS/CSS3**: Modular styling with Sass preprocessing
- **BEM Methodology**: Clean and maintainable CSS architecture
- **Flexbox**: Modern layout system for responsive design
- **Google Fonts**: Inter font family for typography
- **CSS Grid & Flexbox**: Advanced layout techniques

## 📁 Project Structure

```
portfolio/
├── src/
│   ├── index.html              # Main HTML file
│   ├── img/
│   │   └── profile.jpeg        # Profile image
│   ├── resume/
│   │   └── Abdalkarim-Abusalama-resume.pdf
│   └── scss/
│       ├── main.scss           # Main Sass file
│       ├── base/
│       │   ├── _resets.scss    # CSS resets
│       │   └── base.scss       # Base styles
│       ├── blocks/
│       │   ├── _header.scss    # Header component
│       │   ├── _footer.scss    # Footer component
│       │   ├── _intro-banner.scss
│       │   ├── _projects.scss  # Projects section
│       │   ├── _about.scss     # About section
│       │   └── _contact-us.scss
│       └── utils/
│           ├── _variables.scss # Sass variables
│           ├── _mixins.scss    # Reusable mixins
│           └── utils.scss      # Utility exports
└── dist/
    ├── main.css               # Compiled CSS
    └── main.css.map           # Source map
```

## 🎨 Design Features

### Color Palette
- **Primary Background**: `#edf3f5`
- **Header Background**: `#f2f3ff`
- **Text Color**: `#000000`
- **Accent Color**: `#257192`
- **Footer Background**: `#000204`

### Typography
- **Font Family**: Inter (Google Fonts)
- **Base Font Size**: 1rem
- **Responsive Text Scaling**

### Animations
- **Fade In**: 2.4s ease-out entrance animation
- **Slide Down**: Title animation (1.2s)
- **Slide Up**: Description animation (1.5s)
- **Hover Effects**: Scale and opacity transitions

## 📱 Responsive Breakpoints

- **Desktop**: Default styles
- **Tablet**: 481px - 780px
- **Mobile**: ≤ 480px

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shomanabd/portfolio-website.git
   cd portfolio-website
   ```

2. **Install dependencies** (if using Sass compiler)
   ```bash
   npm install -g sass
   ```

3. **Compile Sass** (if making changes)
   ```bash
   sass src/scss/main.scss dist/main.css --watch
   ```

4. **Open in browser**
   ```bash
   open src/index.html
   ```

## 👤 Contact

**Abdalkarim Abusalama**
- GitHub: [@shomanabd](https://github.com/shomanabd)
- LinkedIn: [Abdalkarim Abusalama](https://www.linkedin.com/in/abdalkarim-abusalama/)

## 🙏 Acknowledgments

- Google Fonts for the Inter font family
- CSS animations inspired by modern web design trends
- BEM methodology for maintainable CSS architecture

---

⭐ If you found this project helpful, please give it a star on GitHub!
