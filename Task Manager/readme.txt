# Task Manager - Vercel Deploy

A simple, clean task management application built with Next.js and Tailwind CSS, optimized for Vercel deployment.

## Features

- ✅ Add, complete, and delete tasks
- 🔄 Real-time clock display
- 💾 Persistent storage using localStorage
- 📱 Responsive design
- 🎨 Clean, modern UI with Tailwind CSS
- 📊 Progress tracking with visual indicators
- 🔍 Filter tasks by status (all, pending, completed)

## Quick Start

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deploy to Vercel

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel will automatically detect the Next.js framework and deploy

## File Structure

```
├── pages/
│   ├── _app.js          # App component
│   └── index.js         # Main task manager component
├── styles/
│   └── globals.css      # Global styles with Tailwind
├── package.json         # Dependencies
├── tailwind.config.js   # Tailwind configuration
├── postcss.config.js    # PostCSS configuration
└── next.config.js       # Next.js configuration
```

## Built With

- [Next.js](https://nextjs.org/) - React framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Vercel](https://vercel.com/) - Deployment platform

## License

MIT License - feel free to use this project for your own purposes!