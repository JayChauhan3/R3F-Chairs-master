# R3F Chairs

A React Three Fiber project featuring 3D chairs with smooth wobble transitions and interactive animations.

## Features

- **3D Chair Models**: Interactive 3D chair models with smooth animations
- **Smooth Transitions**: Wobble effects and seamless scrolling
- **Modern Tech Stack**: React 18, Three.js, and pnpm
- **Responsive Design**: Works on desktop and mobile devices
- **Dynamic Backgrounds**: Color-changing backgrounds based on section

## Tech Stack

- **React 18.2.0** - Modern React with hooks
- **React Three Fiber 8.15.11** - 3D rendering in React
- **Three.js 0.160.0** - 3D graphics library
- **React Spring 9.7.3** - Smooth animations
- **@react-three/drei 9.88.13** - Useful helpers for React Three Fiber
- **pnpm** - Fast, disk space efficient package manager
- **Sass** - CSS preprocessing

## Installation

```bash
# Clone the repository
git clone https://github.com/JayChauhan3/R3F-Chairs-master.git

# Navigate to the project
cd R3F-Chairs-master

# Install dependencies
pnpm install

# Start the development server
pnpm start
```

## Usage

- **Scroll** to navigate between chair sections
- **Hover** over chairs to see rotation effects
- **Click** navbar items to jump to sections
- **Experience** smooth 3D transitions

## Project Structure

```
src/
├── components/
│   ├── header.js      # Navigation component
│   ├── section.js     # Section wrapper with 3D positioning
│   └── state.js       # Global state management
├── App.js             # Main application component
├── App.scss           # Styling
└── index.js           # Entry point

public/
├── armchair*.gltf     # 3D chair models
├── armchair*.bin      # 3D model binary data
└── textures*/        # Chair texture files
```

## Customization

- Modify content in `src/App.js` HTMLContent components
- Change colors in the bgColor props
- Adjust animations in `src/App.scss`
- Update 3D models in the `public/` folder
- Configure section positions and transitions

## Scripts

```bash
pnpm start      # Start development server
pnpm build      # Build for production
pnpm test       # Run tests
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with React Three Fiber and modern web technologies**
