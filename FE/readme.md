# Frontend Application 🎨

A modern, high-performance React application built with cutting-edge technologies. Features a beautiful UI with Tailwind CSS and Shadcn UI components, powered by Vite's lightning-fast development experience.

## ✨ Features

- ⚡ **Lightning Fast** - Vite's instant hot module replacement (HMR)
- 🎨 **Beautiful UI** - Pre-styled components with Shadcn UI
- 📱 **Fully Responsive** - Mobile-first design approach
- 🔧 **Highly Customizable** - Easy to theme and extend
- 🚀 **Production Ready** - Optimized build with code splitting
- 🎯 **Developer Experience** - Fast refresh, TypeScript support

## 🚀 Tech Stack

- **React.js** - JavaScript library for building user interfaces
- **Vite** - Next generation frontend tooling (4x faster than webpack)
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn UI** - Re-usable components built with Radix UI and Tailwind CSS
- **JavaScript (ES6+)** - Modern JavaScript features

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 18.x or higher recommended)
- npm (v9+) or yarn (v1.22+) or pnpm (v8+)
- Git for version control

## ⚡ Quick Start

Get up and running in 30 seconds:

```bash
cd FE
npm install
npm run dev
```

## 🛠️ Installation Steps

1. Clone the repository:

```bash
git clone https://github.com/your-repo-url.git
cd your-repo-name
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## 📦 Usage

- To build the application for production:

```bash
npm run build
# or
yarn build
# or
pnpm build
```

- To run tests:

```bash
npm test
# or
yarn test
# or
pnpm test
```

## 📁 Project Structure

```
FE/
├── public/              # Static assets (favicons, images)
├── src/
│   ├── assets/         # Images, fonts, icons
│   ├── components/     # Reusable React components
│   │   └── ui/        # Shadcn UI components (Button, Card, etc.)
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utility functions and helpers
│   ├── pages/         # Page components for routing
│   ├── styles/        # Additional CSS files
│   ├── App.jsx        # Root component with routing
│   ├── main.jsx       # Application entry point
│   └── index.css      # Global styles with Tailwind directives
├── index.html          # HTML template
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite configuration
├── tailwind.config.js  # Tailwind customization
├── postcss.config.js   # PostCSS plugins
├── jsconfig.json       # Path aliases configuration
└── .env.example        # Environment variables template
```

## 🎨 Tailwind CSS Configuration

Tailwind CSS is configured in `tailwind.config.js`. You can customize:

- Colors
- Spacing
- Typography
- Breakpoints
- And more...

## 🧩 Shadcn UI Components

Shadcn UI components are located in `src/components/ui/`. To add new components:

```bash
npx shadcn-ui@latest add [component-name]
```

Example:

```bash
npx shadcn-ui@latest add button
npx shadcn-ui@latest add card
npx shadcn-ui@latest add dialog
```

## 📜 Available Scripts

| Script            | Description              |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Build for production     |
| `npm run preview` | Preview production build |
| `npm run lint`    | Run ESLint               |

## 🔧 Configuration Files

- **vite.config.js** - Vite configuration
- **tailwind.config.js** - Tailwind CSS configuration
- **postcss.config.js** - PostCSS configuration
- **jsconfig.json** - JavaScript configuration for path aliases

## 📦 Dependencies

Key dependencies include:

- react & react-dom
- tailwindcss
- @radix-ui/\* (for Shadcn UI)
- class-variance-authority
- clsx & tailwind-merge

## 🌐 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=your_api_url_here
```

Access in your code:

```javascript
const apiUrl = import.meta.env.VITE_API_URL;
```

## 🎯 Best Practices

### Component Development
- ✅ Use functional components and React hooks
- ✅ Keep components small, focused, and reusable
- ✅ Use meaningful component and variable names
- ✅ Implement proper prop validation

### Styling
- ✅ Prefer Tailwind utility classes over custom CSS
- ✅ Use Shadcn UI components for consistent design
- ✅ Follow mobile-first responsive design
- ✅ Extract repeated utility patterns into custom components

### Code Organization
- ✅ Group related files by feature/module
- ✅ Use absolute imports with path aliases
- ✅ Keep business logic separate from UI components
- ✅ Write clean, self-documenting code

### Performance
- ✅ Lazy load routes and heavy components
- ✅ Optimize images and assets
- ✅ Use React.memo for expensive components
- ✅ Implement code splitting for large bundles

## 📚 Additional Resources

- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Shadcn UI Documentation](https://ui.shadcn.com/)

## 🤝 Contributing

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
