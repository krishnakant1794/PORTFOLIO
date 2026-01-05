# 🚀 3D Animated Portfolio Website

A stunning, interactive 3D-animated portfolio website showcasing my projects, skills, and experience as a Full Stack Developer. Built with modern web technologies and featuring immersive 3D animations powered by Three.js.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-3D%20Animated-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)

## ✨ Features

### 🎨 3D Animations & Effects
- **Interactive 3D Particle System**: Dynamic particle effects in the hero section
- **Rotating Geometric Shapes**: Animated torus, octahedron, and icosahedron
- **Mouse-Responsive Camera**: Camera movement follows mouse cursor
- **3D Flip Cards**: Interactive about section with card flip animations
- **3D Project Cards**: Hover effects with depth and perspective
- **3D Skill Orbs**: Rotating skill display cards
- **Parallax Scrolling**: Smooth parallax effects on scroll

### 🎯 Interactive Elements
- **Smooth Scrolling Navigation**: Seamless section transitions
- **3D Button Effects**: Interactive buttons with tilt and hover effects
- **Animated Text**: 3D text effects in hero section
- **Scroll Animations**: Fade-in animations on scroll
- **Contact Form**: 3D-styled contact form with validation

### 📱 Responsive Design
- Fully responsive layout for all screen sizes
- Mobile-optimized navigation
- Adaptive grid layouts
- Touch-friendly interactions

## 🛠️ Tech Stack

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with gradients, animations, and 3D transforms
- **JavaScript (ES6+)**: Modern JavaScript features
- **Three.js**: 3D graphics and animations library

### Libraries & Frameworks
- **Three.js r128**: For 3D scene rendering and particle systems
- **Google Fonts (Poppins)**: Modern typography

## 📋 Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for CDN resources)
- No build tools or package managers required!

## 🚀 Getting Started

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/portfolio-website.git
   cd portfolio-website
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Navigate to `http://localhost:8000` (if using a server)
   - Or directly open `index.html` in your browser

## 📁 Project Structure

```
portfolio-website/
│
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript and Three.js code
└── README.md           # Project documentation
```

## 🎮 Usage

### Navigation
- Click on navigation links to smoothly scroll to different sections
- Use the "View My Work" button to jump to projects
- Use the "Get In Touch" button to jump to contact section

### Interactive Features
- **Hover over project cards**: See 3D tilt effects and project details
- **Hover over skill orbs**: Experience 3D rotation effects
- **Move your mouse**: Watch the 3D camera follow your cursor
- **Scroll down**: Enjoy parallax effects and fade-in animations

### Customization

#### Update Personal Information
1. Edit `index.html`:
   - Change name in hero section (line ~31)
   - Update about section text (line ~68-70)
   - Modify skills section (line ~139-171)
   - Update contact information (line ~196-208)

#### Change Profile Photo
Replace the image URL in `index.html` (line ~53):
```html
<img src="YOUR_IMAGE_URL" alt="Your Name" class="profile-photo">
```

#### Update Projects
Modify the projects section in `index.html` (line ~86-140):
- Change project titles, descriptions, and tech stacks
- Update project links
- Add or remove project cards

#### Customize Colors
Edit CSS variables in `styles.css` (line ~8-14):
```css
:root {
    --primary-color: #6366f1;    /* Change primary color */
    --secondary-color: #8b5cf6;  /* Change secondary color */
    --accent-color: #ec4899;     /* Change accent color */
    --bg-dark: #0a0a0f;          /* Change dark background */
    --bg-light: #1a1a2e;         /* Change light background */
}
```

#### Modify 3D Effects
Edit `script.js` to customize:
- Particle count and colors (line ~40-60)
- Geometric shapes (line ~75-110)
- Animation speeds (line ~157-180)

## 🎨 Sections

### 🏠 Hero Section
- Animated 3D particle background
- Rotating geometric shapes
- Interactive 3D text
- Call-to-action buttons

### 👤 About Section
- 3D flip card with profile photo
- Education and experience details
- Company information
- Personal introduction

### 💼 Projects Section
- 4 featured projects with:
  - Project descriptions
  - Tech stack information
  - Client feedback
  - Live project links

### 🎯 Skills Section
- Frontend technologies
- Backend technologies
- Mobile development
- 3D interactive orbs

### 📧 Contact Section
- 3D contact form
- Contact information cards
- Social media links

## 🌐 Live Projects Showcased

1. **ThinkArena** - Dynamic quiz application
   - [Live Demo](https://thinkarena.netlify.app/)
   - Tech: React.js, React Router DOM, JavaScript

2. **Sudoku Master** - Classic Sudoku game
   - [Live Demo](https://krishnakant1794.github.io/Sudoku-Master/)
   - Tech: HTML5, CSS3, Tailwind CSS, JavaScript

3. **Chitrika** - E-commerce platform for handmade paintings
   - [Live Demo](https://chitrika.vercel.app/login)
   - Tech: React.js, Node.js, MongoDB, Firebase, Razorpay

4. **AwaazNow** - AI-powered news summarizer
   - [Live Demo](https://awazz-now-krishnakant-kumars-projects.vercel.app/login)
   - Tech: React.js, Node.js, MongoDB, Google Gemini AI

## 👨‍💻 About the Developer

**Krishnakant Kumar**

- 🎓 Computer Science & Engineering student at Central University of Jharkhand
- 🚀 Full Stack Developer & Co-Founder at [KA Web & App Developers](https://www.webappdeveloper.online/)
- 💼 2+ years of experience in web and mobile app development
- 🎯 Specialized in building modern websites and mobile applications

### Skills
- **Frontend**: React.js, JavaScript, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Mobile**: Flutter, Dart
- **Tools**: Git, VS Code, Firebase, Razorpay

## 🎯 Key Features Explained

### 3D Particle System
The hero section features a dynamic particle system with 1000 particles that rotate and respond to mouse movement, creating an immersive 3D environment.

### Interactive Cards
All cards (about, projects, skills) feature 3D transformations that respond to mouse hover, creating depth and interactivity.

### Smooth Animations
The website uses CSS animations and JavaScript for smooth transitions, fade-ins, and scroll effects.

### Performance Optimized
- Efficient Three.js rendering
- Optimized particle count
- Smooth 60fps animations
- Lightweight codebase

## 🐛 Troubleshooting

### 3D Effects Not Working
- Ensure you have a modern browser with WebGL support
- Check browser console for errors
- Verify Three.js CDN is loading correctly

### Images Not Loading
- Check image URLs are correct
- Ensure images are publicly accessible
- Verify CORS settings if hosting externally

### Animations Lagging
- Reduce particle count in `script.js` (line ~40)
- Close other browser tabs
- Check device performance

## 📝 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not supported)

## 🔄 Future Enhancements

- [ ] Add dark/light mode toggle
- [ ] Implement blog section
- [ ] Add project filtering
- [ ] Add more 3D models
- [ ] Implement PWA features
- [ ] Add analytics integration
- [ ] Multi-language support

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/portfolio-website/issues).

## 📧 Contact

**Krishnakant Kumar**

- 🌐 Company Website: [KA Web & App Developers](https://www.webappdeveloper.online/)
- 📧 Email: [Your Email]
- 💼 LinkedIn: [Your LinkedIn]
- 🐙 GitHub: [Your GitHub]

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) - 3D graphics library
- [Google Fonts](https://fonts.google.com/) - Poppins font family
- All the amazing developers in the open-source community

## ⭐ Show Your Support

If you like this project, please give it a ⭐ on GitHub!

---

**Made with ❤️ by Krishnakant Kumar**

*Building digital experiences that matter*

