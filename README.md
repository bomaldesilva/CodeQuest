# CodeQuest 2025 🚀

**The Ultimate Competitive Programming Challenge**

Organized by IEEE UCSC Student Branch

![CodeQuest 2025](https://img.shields.io/badge/CodeQuest-2025-blue?style=for-the-badge&logo=code)
![IEEE UCSC](https://img.shields.io/badge/IEEE-UCSC-red?style=for-the-badge&logo=ieee)

## 🌟 Features

### ✨ **Modern Design System**
- **Dark/Light Theme Toggle** - Seamless theme switching
- **Responsive Design** - Perfect on all devices
- **Google Fonts Integration** - Inter, Poppins, JetBrains Mono
- **Font Awesome Icons** - Professional iconography
- **CSS Variables** - Consistent design tokens
- **SCSS Architecture** - Modular and maintainable

### 🎨 **Visual Enhancements**
- **Animated UCSC Logo** - Custom SVG with glow effects
- **Gradient Backgrounds** - Dynamic hero section
- **Floating Elements** - Subtle background animations
- **Smooth Transitions** - Professional micro-interactions
- **Text Shadows** - Enhanced readability in dark mode
- **Hover Effects** - Interactive UI elements

### 📱 **Mobile-First Responsive**
- **Mobile Menu** - Hamburger menu with smooth animations
- **Touch-Friendly** - Optimized for mobile interaction
- **Responsive Grid** - Adaptive layouts
- **Mobile Navigation** - Full-screen overlay menu

### 🏆 **Prize Section**
- **3+1 Layout** - 3 cards in top row, 1 centered below
- **Staggered Animations** - Sequential card reveals
- **Hover Effects** - Interactive prize cards
- **Professional Styling** - Clean, modern design

### 📋 **Interactive Elements**
- **FAQ Accordion** - Expandable questions
- **Registration Form** - Complete participant form
- **Timeline Animation** - Animated event timeline
- **Stats Counter** - Animated statistics
- **Smooth Scrolling** - Navigation enhancements

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bomaldesilva/CodeQuest.git
   cd CodeQuest
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   - Navigate to `http://localhost:3000`
   - The site will automatically reload on changes

## 📁 Project Structure

```
codequest-2025/
├── index.html          # Main HTML file
├── styles.scss         # SCSS source file
├── styles.css          # Compiled CSS
├── package.json        # Project configuration
├── README.md          # Project documentation
└── doc.txt            # Original requirements
```

## 🎯 Key Sections

### 🏠 **Hero Section**
- **Animated Title** - Typing effect
- **Gradient Background** - Dynamic colors
- **Floating Icons** - Background elements
- **Call-to-Action** - Registration buttons
- **Enhanced Text Visibility** - Perfect contrast in dark mode

### 📖 **About Section**
- **Feature List** - Key event highlights
- **Statistics Cards** - Animated counters
- **Grid Layout** - Responsive design
- **Icon Integration** - Font Awesome icons

### 📅 **Timeline Section**
- **Interactive Timeline** - Click to expand
- **Responsive Design** - Mobile-optimized
- **Animation Effects** - Smooth transitions
- **Icon Integration** - Visual indicators

### 🏆 **Prizes Section**
- **Special Layout** - 3+1 card arrangement
- **Hover Animations** - Interactive effects
- **Professional Design** - Clean styling
- **Responsive Grid** - Mobile-friendly

### ❓ **FAQ Section**
- **Accordion Style** - Expandable questions
- **Smooth Animations** - Professional transitions
- **Icon Integration** - Visual indicators
- **Mobile Optimized** - Touch-friendly

### 📝 **Registration Form**
- **Complete Form** - All participant details
- **Validation** - Client-side validation
- **Responsive Design** - Mobile-friendly
- **Professional Styling** - Clean interface

## 🎨 Design System

### **Color Palette**

#### Dark Theme
```css
--primary-bg: #0a0a0a
--secondary-bg: #1a1a1a
--accent-color: #00d4ff
--text-primary: #ffffff
--text-secondary: #b0b0b0
```

#### Light Theme
```css
--primary-bg: #ffffff
--secondary-bg: #f8f9fa
--accent-color: #2563eb
--text-primary: #1f2937
--text-secondary: #4b5563
```

### **Typography**
- **Primary Font**: Inter (Body text)
- **Heading Font**: Poppins (Titles)
- **Monospace Font**: JetBrains Mono (Code)

### **Spacing System**
```css
--spacing-xs: 0.25rem
--spacing-sm: 0.5rem
--spacing-md: 1rem
--spacing-lg: 1.5rem
--spacing-xl: 2rem
--spacing-2xl: 3rem
--spacing-3xl: 4rem
```

## 🔧 Customization

### **Theme Colors**
Edit the CSS variables in `styles.scss`:

```scss
:root {
  --accent-color: #00d4ff;
  --accent-secondary: #0099cc;
  --accent-tertiary: #ff6b35;
}
```

### **Fonts**
Update Google Fonts import in `styles.scss`:

```scss
@import url('https://fonts.googleapis.com/css2?family=YourFont:wght@400;600;700&display=swap');
```

### **Animations**
Modify animation durations in `styles.scss`:

```scss
--transition-fast: 0.15s ease;
--transition-normal: 0.3s ease;
--transition-slow: 0.5s ease;
```

## 📱 Responsive Design

### **Breakpoints**
- **Mobile**: `max-width: 768px`
- **Tablet**: `max-width: 1024px`
- **Desktop**: `min-width: 1025px`

### **Mobile Features**
- **Hamburger Menu** - Full-screen overlay
- **Touch-Friendly** - Larger touch targets
- **Optimized Layout** - Single-column design
- **Fast Loading** - Optimized assets

## ⚡ Performance

### **Optimizations**
- **Minified CSS** - Compressed styles
- **Optimized Images** - WebP format
- **Lazy Loading** - Deferred loading
- **CDN Resources** - Fast loading

### **Best Practices**
- **Semantic HTML** - Accessible markup
- **CSS Grid/Flexbox** - Modern layouts
- **Progressive Enhancement** - Graceful degradation
- **Mobile-First** - Responsive design

## 🛠️ Development

### **Available Scripts**

```bash
npm run start      # Start development server
npm run build      # Build production CSS
npm run watch      # Watch SCSS changes
npm run dev        # Development mode (watch + server)
npm run lint       # Lint JavaScript files
npm run format     # Format code with Prettier
npm run optimize   # Build and format
```

### **SCSS Structure**
```scss
// Variables & Imports
// Reset & Base Styles
// Typography
// Utility Classes
// Navigation
// Hero Section
// Buttons
// Sections
// Timeline
// Prize Cards
// FAQ
// Forms
// Footer
// Animations
// Responsive Design
```

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile**: iOS 14+, Android 10+

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

### **IEEE UCSC Student Branch Web Team**
- **Project Lead**: Bomal De Silva
- **Frontend Developer**: Bomal De Silva
- **UI/UX Designer**: Bomal De Silva

### **Contact**
- **Email**: codequest@ucscieee.lk
- **Website**: https://ucscieee.lk
- **Phone**: +94 11 258 1245

## 🙏 Acknowledgments

- **IEEE UCSC Student Branch** - Event organization
- **Google Fonts** - Typography
- **Font Awesome** - Icons
- **jQuery** - JavaScript library
- **Sass** - CSS preprocessor

## 📈 Future Enhancements

- [ ] **Real-time Leaderboard** - Live competition updates
- [ ] **Participant Dashboard** - Personal progress tracking
- [ ] **Workshop Integration** - Learning resources
- [ ] **Social Media Integration** - Sharing features
- [ ] **Multi-language Support** - Internationalization
- [ ] **PWA Features** - Offline capabilities
- [ ] **Analytics Integration** - Performance tracking
- [ ] **Accessibility Improvements** - WCAG compliance

---

**Made by IEEE UCSC Student Branch**

*Empowering the next generation of programmers*
