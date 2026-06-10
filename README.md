# SPBU Medical Education Portal

A comprehensive English-language website for SPBU (Saint Petersburg State University) medical students, featuring dedicated sections for **Histology** and **Chemistry**.

## 🎯 Features

### Navigation Menu
- **Home** - Welcome section with call-to-action
- **Histology** - Complete section with:
  - Introduction to histology
  - Main topics (tissue types, cellular structures, microscopy)
  - Learning resources (study guides, videos, slides, practice exams)
  - Interactive quiz section
  
- **Chemistry** - Complete section with:
  - Introduction to chemistry
  - Main topics (atomic structure, organic chemistry, biochemistry)
  - Learning resources (study guides, molecular models, problem sets, virtual labs)
  - Interactive quiz section

- **About** - Information about the portal
- **Contact** - Contact form for inquiries

### Key Components

1. **Responsive Navigation Bar**
   - Dropdown menus for Histology and Chemistry subjects
   - Mobile-friendly hamburger menu
   - Sticky navigation for easy access

2. **Hero Section**
   - Engaging welcome message
   - Call-to-action button

3. **Content Sections**
   - Well-organized topics with clear hierarchies
   - Resource cards with icons
   - Practice materials and quizzes

4. **Interactive Features**
   - Smooth scrolling navigation
   - Mobile-responsive design
   - Scroll animations
   - Working contact form

5. **Professional Styling**
   - Modern color scheme (Blue & Green)
   - Clean typography
   - Smooth transitions and hover effects
   - Mobile-first responsive design

## 📁 Files Structure

```
usmle/
├── index.html      # Main HTML structure
├── styles.css      # Complete styling and responsive design
├── script.js       # Interactive functionality and animations
└── README.md       # This file
```

## 🚀 Getting Started

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/AhmedRamadanimat/usmle.git
   cd usmle
   ```

2. Open `index.html` in your web browser (no server required for basic functionality)

3. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment
1. The site is ready for GitHub Pages
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your site will be available at `https://AhmedRamadanimat.github.io/usmle/`

## 🎨 Design Details

### Color Scheme
- **Primary Blue**: `#1e3a8a` - Main color for headers and nav
- **Secondary Blue**: `#3b82f6` - Hover states and highlights
- **Accent Green**: `#10b981` - Call-to-action buttons
- **Light Gray**: `#f9fafb` - Backgrounds

### Typography
- Font Family: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Responsive font sizes for mobile and desktop

### Responsive Breakpoints
- **Desktop**: 768px and above
- **Tablet**: 480px - 768px
- **Mobile**: Below 480px

## 📚 Content Sections

### Histology Curriculum
- Basic tissue types (epithelial, connective, muscle, nervous)
- Cellular structures and organelles
- Organ systems histology
- Microscopy techniques
- Pathological histology

### Chemistry Curriculum
- Atomic structure and bonding
- Organic chemistry fundamentals
- Biochemistry basics
- Chemical reactions and equilibrium
- pH and buffer systems

## ✨ Interactive Features

- **Smooth Navigation**: Click any link and scroll smoothly to sections
- **Dropdown Menus**: Subject-specific submenus
- **Mobile Menu**: Hamburger menu for mobile devices
- **Scroll Animations**: Elements fade in as you scroll
- **Quiz Integration**: Ready for quiz functionality (coming soon)
- **Contact Form**: Functional contact form with validation

## 🔧 Future Enhancements

- [ ] Interactive quiz system with scoring
- [ ] Discussion forums for students
- [ ] Video lecture integration
- [ ] PDF study materials download
- [ ] Progress tracking system
- [ ] Peer-to-peer study groups
- [ ] Real-time collaboration tools
- [ ] Mobile app version

## 📝 How to Customize

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e3a8a;
    --secondary-color: #3b82f6;
    --accent-color: #10b981;
    /* ... other colors ... */
}
```

### Add New Topics
1. Open `index.html`
2. Find the relevant section (Histology or Chemistry)
3. Add new `<li>` items to the topics list

### Update Content
Simply edit the text in the HTML sections with your preferred content editor.

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create your feature branch
3. Make your changes
4. Submit a pull request

## 📧 Contact & Support

For questions or suggestions, please use the contact form on the website or reach out via GitHub Issues.

## 📄 License

This project is open source and available under the MIT License.

---

**Created for**: SPBU Medical Education  
**Last Updated**: June 2026  
**Version**: 1.0.0
