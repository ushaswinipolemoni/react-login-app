# React Login App

A beautiful, modern login page built with React and Vite, featuring premium design aesthetics and smooth animations.

## Features

- 🎨 **Premium Design** - Glassmorphism UI with gradient accents and smooth animations
- 🌙 **Dark Theme** - Eye-friendly dark color scheme with vibrant accents
- 🔐 **Social Login** - Integration-ready Google, GitHub, and Apple login buttons
- ✨ **Smooth Animations** - Micro-interactions and floating background elements
- 📱 **Responsive** - Works beautifully on all screen sizes
- ⚡ **Fast** - Built with Vite for lightning-fast development and builds

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to the URL shown in the terminal (usually `http://localhost:5173`)

### Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist` directory.

## Project Structure

```
/
├── src/
│   ├── components/
│   │   └── LoginPage.jsx    # Main login page component
│   ├── App.jsx              # Root component
│   ├── main.jsx             # Entry point
│   └── index.css            # Design system and global styles
├── index.html               # HTML template
├── vite.config.js           # Vite configuration
└── package.json             # Project dependencies
```

## Customization

The design system is defined in `src/index.css` using CSS custom properties (variables). You can easily customize:

- **Colors**: Modify the color palette in the `:root` section
- **Spacing**: Adjust spacing variables for consistent layouts
- **Typography**: Change font families and sizes
- **Animations**: Tweak transition timings and effects

## Technologies Used

- **React 18** - UI library
- **Vite 5** - Build tool and dev server
- **CSS3** - Styling with modern features (Custom Properties, Grid, Flexbox)
- **Google Fonts** - Inter font family

## License

MIT
