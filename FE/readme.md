# Frontend Application

A modern React application built with Vite, styled with Tailwind CSS and Shadcn UI components.

## 🚀 Tech Stack

- **React.js** - JavaScript library for building user interfaces
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn UI** - Re-usable components built with Radix UI and Tailwind CSS
- **JavaScript** - Programming language

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 16.x or higher)
- npm or yarn or pnpm

## 🛠️ Installation

1. Navigate to the frontend directory:
```bash
cd FE
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

## 🏃 Running the Application

### Development Mode
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

The application will start on `http://localhost:5173`

### Build for Production
```bash
npm run build
# or
yarn build
# or
pnpm build
```

### Preview Production Build
```bash
npm run preview
# or
yarn preview
# or
pnpm preview
```

## 📁 Project Structure

```
FE/
├── public/              # Static assets
├── src/
│   ├── assets/         # Images, fonts, etc.
│   ├── components/     # Reusable components
│   │   └── ui/        # Shadcn UI components
│   ├── lib/           # Utility functions
│   ├── App.jsx        # Root component
│   ├── main.jsx       # Entry point
│   └── index.css      # Global styles with Tailwind
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
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

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## 🔧 Configuration Files

- **vite.config.js** - Vite configuration
- **tailwind.config.js** - Tailwind CSS configuration
- **postcss.config.js** - PostCSS configuration
- **jsconfig.json** - JavaScript configuration for path aliases

## 📦 Dependencies

Key dependencies include:
- react & react-dom
- tailwindcss
- @radix-ui/* (for Shadcn UI)
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

- Use functional components and hooks
- Keep components small and focused
- Use Tailwind utility classes for styling
- Leverage Shadcn UI components for consistent design
- Follow the project structure for better organization

## 📚 Additional Resources

- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Shadcn UI Documentation](https://ui.shadcn.com/)

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## 📄 License

[Specify your license here]