# 📸 Instagram Clone

A modern, responsive Instagram clone built with vanilla HTML, CSS, and JavaScript. This project recreates Instagram's core UI/UX features and provides a solid foundation for learning front-end web development.

![Instagram Clone Preview](https://via.placeholder.com/800x400/E1306C/FFFFFF?text=Instagram+Clone+Preview)

## ✨ Features

### 🎨 **User Interface**
- Pixel-perfect recreation of Instagram's modern design
- Clean, intuitive layout with attention to detail
- Smooth animations and transitions

### 👤 **User Profiles**
- Dynamic user profiles with avatars and bios
- Post, followers, and following counts
- Profile picture integration across the app

### 📱 **Posts & Feed**
- Interactive post feed with sample content
- Like and unlike functionality with heart animations
- Comment system with real-time interactions
- Post engagement metrics

### 📚 **Stories**
- Horizontal scrollable stories section
- Story indicators and navigation
- Responsive story viewer experience

### 📱 **Responsive Design**
- Mobile-first approach
- Seamless experience across desktop, tablet, and mobile
- Adaptive layouts for different screen sizes

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure and accessibility |
| **CSS3** | Modern styling, Flexbox/Grid, animations |
| **JavaScript (ES6+)** | Interactive functionality and DOM manipulation |

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/euii-ii/insta-clone.git
   cd insta-clone
   ```

2. **Launch the application**
   ```bash
   # Option 1: Open directly in browser
   open index.html
   
   # Option 2: Using Live Server (VS Code extension)
   # Right-click on index.html and select "Open with Live Server"
   
   # Option 3: Using Python (if installed)
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 📱 Usage

### Navigation
- **Home Feed**: Scroll through posts, like, and comment
- **Stories**: Click through story thumbnails at the top
- **Profile**: View user information and post galleries

### Interactions
- **❤️ Like Posts**: Click the heart icon or double-tap images
- **💬 Comments**: Add comments using the input field
- **📖 Stories**: Navigate through stories with arrow controls

## 📁 Project Structure

```
insta-clone/
├── index.html          # Main HTML file
├── css/
│   ├── style.css       # Main stylesheet
│   └── responsive.css  # Media queries
├── js/
│   ├── main.js         # Core functionality
│   ├── posts.js        # Post interactions
│   └── stories.js      # Stories functionality
├── assets/
│   ├── images/         # Sample images
│   └── icons/          # UI icons
└── README.md
```

## 🎯 Key Learning Objectives

- **Responsive Web Design**: Mobile-first CSS and flexible layouts
- **DOM Manipulation**: Dynamic content updates with JavaScript
- **Event Handling**: User interactions and form submissions
- **CSS Animations**: Smooth transitions and micro-interactions
- **Code Organization**: Modular JavaScript and maintainable CSS

## 🔧 Customization

### Adding New Posts
```javascript
// In js/posts.js
const newPost = {
    id: generateId(),
    username: 'your_username',
    image: 'path/to/image.jpg',
    caption: 'Your caption here',
    likes: 0,
    comments: []
};
```

### Styling Modifications
```css
/* In css/style.css */
:root {
    --primary-color: #E1306C;
    --background-color: #FAFAFA;
    --text-color: #262626;
    /* Modify these variables to change the theme */
}
```

## 🌟 Future Enhancements

- [ ] Dark mode toggle
- [ ] User authentication simulation
- [ ] Local storage for likes/comments
- [ ] Image upload functionality
- [ ] Search and explore page
- [ ] Direct messaging interface
- [ ] Progressive Web App (PWA) features

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **🍴 Fork the repository**
2. **🌟 Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **💫 Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **🚀 Push to the branch** (`git push origin feature/amazing-feature`)
5. **📝 Open a Pull Request**

### Development Guidelines
- Follow existing code style and conventions
- Test on multiple browsers and devices
- Add comments for complex functionality
- Update documentation when needed

## 📸 Screenshots

| Desktop View | Mobile View |
|-------------|-------------|
| ![Desktop](https://via.placeholder.com/400x300/E1306C/FFFFFF?text=Desktop+View) | ![Mobile](https://via.placeholder.com/200x350/E1306C/FFFFFF?text=Mobile+View) |

## 🐛 Known Issues

- Stories navigation may not work properly on older browsers
- Some animations might be reduced on low-performance devices

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**euii-ii**
- GitHub: [@euii-ii](https://github.com/euii-ii)
- Project Link: [Instagram Clone](https://github.com/euii-ii/insta-clone)

## 🙏 Acknowledgments

- Instagram for design inspiration
- [Unsplash](https://unsplash.com) for sample images
- The web development community for best practices

---

⭐ **Star this repository if you found it helpful!** ⭐
