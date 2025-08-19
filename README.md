# React Template

A simple React + Vite starter template with everything you need to get started quickly.

## What's Inside

- ⚛️ **React 19** + **TypeScript** + **Vite**
- 🎨 **Tailwind CSS** for styling
- 🧩 **shadcn/ui** components
- 🚦 **React Router** for navigation
- 🐻 **Zustand** for state management
- 📝 **React Hook Form** + **Zod** for forms
- 🔄 **TanStack Query** for data fetching
- ✨ **ESLint** for code quality

## Getting Started

```bash
# Clone the template
git clone <your-repo-url>
cd react-template

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) and start building!

## Scripts

```bash
npm run dev      # Development server
npm run build    # Build for production
npm run lint     # Run linter
```

## Project Structure

```
src/
├── components/     # UI components
├── pages/         # Page components
├── hooks/         # Custom hooks
├── stores/        # Zustand stores
├── routes/        # Router setup
└── lib/           # Utilities
```

## Adding Components

```bash
# Add shadcn/ui components
npx shadcn@latest add button
npx shadcn@latest add input
```

## Deployment

Build and deploy anywhere:

```bash
npm run build
# Upload the `dist` folder to your hosting service
```

Works great with Vercel, Netlify, or any static hosting.

---

That's it! Start coding 🚀
