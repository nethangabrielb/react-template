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
- 🔔 **Sonner** for toast notifications
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

**Note:** Some empty directories contain `.gitkeep` files to ensure they're tracked in Git. Remember to remove these `.gitkeep` files when you add your own files to these directories.

## Adding Components
```bash
# Add shadcn/ui components
npx shadcn@latest add button
npx shadcn@latest add input
```

## Working with Empty Directories
This template includes `.gitkeep` files in empty directories to ensure they're preserved in version control. When you start adding your own files to these directories:

1. Add your new files (components, hooks, etc.)
2. Remove the corresponding `.gitkeep` file
3. Commit your changes

Example:
```bash
# After adding a new component to src/components/
rm src/components/.gitkeep
git add src/components/YourNewComponent.tsx
git commit -m "Add new component, remove .gitkeep"
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
