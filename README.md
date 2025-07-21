# 📋 TaskMaster Pro

<div align="center">
  <p>A modern, responsive task management application with a beautiful UI and powerful features</p>
  
  <!-- Version Badges -->
  <div style="display: flex; justify-content: center; gap: 10px; margin: 15px 0;">
    <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&style=for-the-badge" alt="React">
    <img src="https://img.shields.io/badge/Tailwind_CSS-3.3.0-06B6D4?logo=tailwindcss&style=for-the-badge" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Vite-4.0.0-646CFF?logo=vite&style=for-the-badge" alt="Vite">
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  </div>
  
  <img src="/public/images/screenshot.png" alt="TaskMaster Pro Screenshot" style="max-width: 100%; border-radius: 10px; margin: 20px 0; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
</div>

![Home Page](https://github.com/user-attachments/assets/de280861-89ab-4dde-9ad1-b065b0f08baa)

![add task](https://github.com/user-attachments/assets/a7d2a373-301f-49f5-bcab-89f0e9f8e48f)

![complete task](https://github.com/user-attachments/assets/deb71144-0f4c-427c-9083-657b108031a5)




 🎯 Key Features

**📝 Task Management**

-Add Tasks - Quickly add new tasks with intuitive input

-Edit Inline - Double-click to edit tasks directly

-Mark Complete - Toggle task completion status

-Delete Tasks- Remove tasks you no longer need

**🎨 User Experience**

- 🌓 **Dark/Light Mode** - Automatic system theme detection

- 📱 **Fully Responsive** - Works on all device sizes

- ⚡ **Blazing Fast** - Built with Vite for optimal performance

- 🎭 **Smooth Animations** - Delightful UI interactions

### 🔍 Smart Organization

- **Filter Tasks** - View All/Active/Completed tasks

- **Persistent Storage** - Tasks saved in local storage

- **Task Timestamps** - See when tasks were created

## 🛠 Tech Stack

### Core Technologies
| Technology | Purpose | Version |

|------------|---------|---------|

| React | UI Framework | 18.2.0 |

| Vite | Build Tool | 4.0.0 |

| Tailwind CSS | Styling | 3.3.0 |

| React Icons | Icon Library | 4.8.0 |

| PostCSS | CSS Processing | 8.4.0 |

| Autoprefixer | CSS Compatibility | 10.4.0 |

### Development Dependencies

- ESLint - Code linting

- Prettier - Code formatting

- PostCSS - CSS processing

- Vite - Development server & build

## 🚀 Quick Start Guide

 **Prerequisites**

- Node.js 16.14.0 or later
- npm (comes with Node.js) or Yarn

**** Installation****

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskmaster-pro.git
   cd taskmaster-pro
   ```

2. **Install dependencies**
   ```bash
   # Using npm
   npm install
   
   # OR using Yarn
   yarn
   ```

3. **Start the development server**
   ```bash
   # Using npm
   npm run dev
   
   # OR using Yarn
   yarn dev
   ```

4. **Open in your browser**
   Visit [http://localhost:3000](http://localhost:3000) to see the app in action!

## 🏗 Project Structure

```
taskmaster-pro/
├── public/                 # Static files
│   ├── images/             # Image assets
│   └── index.html          # Main HTML file
│
├── src/                    # Source files
│   ├── App.jsx             # Main application component
│   ├── main.jsx            # Application entry point
│   └── index.css           # Global styles
│
├── .gitignore              # Git ignore file
├── package.json            # Project dependencies
├── tailwind.config.js      # Tailwind CSS configuration
├── postcss.config.js       # PostCSS configuration
└── vite.config.js          # Vite configuration
```

### Key Files Explained

- `src/App.jsx` - Main application component containing all the logic

- `src/main.jsx` - Renders the React app to the DOM

- `src/index.css` - Global styles and Tailwind directives

- `public/index.html` - Base HTML template

- `tailwind.config.js` - Tailwind CSS configuration

- `vite.config.js` - Vite build configuration

## 📦 Build & Deploy

### Build for Production
```bash
npm run build

# or

yarn build
```

### Preview Production Build
```bash
npm run preview

# or

yarn preview
```

## 🎨 Customization

### Theme Configuration
Edit `tailwind.config.js` to customize:
- Color schemes
- Font families
- Breakpoints
- Animations

Example:
```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: {
          DEFAULT: '#3B82F6',
          dark: '#2563EB',
        },
      },
      animation: {
        'bounce-slow': 'bounce 3s infinite',
      }
    },
  },
}
```

## 🤝 Contributing

1. Fork the repository

2. Create your feature branch (`git checkout -b feature/AmazingFeature`)

3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)

4. Push to the branch (`git push origin feature/AmazingFeature`)

5. Open a Pull Request


## 👨‍💻 Author

**Ankit Maurya**
- GitHub: [Ankit Maurya](https://github.com/Ankit-Maurya17/))

- LinkedIn: [Ankit Maurya](https://www.linkedin.com/in/ankit-maurya-467b61342/))

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - The library for web and native user interfaces

- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework

- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling

- [Feather Icons](https://feathericons.com/) - Simply beautiful open source icons

---

<div align="center">
  Built with ❤️ using modern web technologies
</div>


