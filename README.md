# ⚖️ المستشار القانوني
### Legal Advisor System | React + TypeScript + Tailwind CSS

---

## 📌 Overview

A smart **Arabic legal consultation system** built with React and TypeScript. The application provides an intelligent interface for legal advisory services, featuring a modern RTL (Right-to-Left) design optimized for Arabic-speaking users.

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| React | 18+ | UI Framework |
| TypeScript | 5+ | Type Safety |
| Tailwind CSS | 3+ | Styling |
| Vite | 5+ | Build Tool & Dev Server |
| Bun | Latest | Package Manager |
| shadcn/ui | Latest | UI Components |
| Vitest | Latest | Unit Testing |

---

## 📁 Project Structure

```
legal-advisor/
│
├── src/
│   └── main.tsx              # Application entry point
│
├── index.html                # Root HTML (Arabic lang, RTL meta)
├── tailwind.config.ts        # Tailwind + custom colors & animations
├── vite.config.ts            # Vite configuration
├── vitest.config.ts          # Test configuration
├── tsconfig.json             # TypeScript config
├── components.json           # shadcn/ui components config
├── package.json              # Dependencies
├── bun.lock                  # Bun lockfile
└── .gitignore
```

---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js 18+ or Bun
- npm / bun

### Install with Bun (Recommended)
```bash
bun install
```

### Install with npm
```bash
npm install
```

---

## 🚀 Running the App

### Development Server
```bash
# With Bun
bun run dev

# With npm
npm run dev
```

Open: `http://localhost:5173`

### Production Build
```bash
# With Bun
bun run build

# With npm
npm run build
```

### Run Tests
```bash
# With Bun
bun run test

# With npm
npm run test
```

### Preview Production Build
```bash
bun run preview
# or
npm run preview
```

---

## 🎨 Design System

### Custom Fonts
```typescript
fontFamily: {
  display: ["var(--font-display)", "serif"],   // Headings
  body:    ["var(--font-body)", "sans-serif"], // Body text
}
```

### Color Tokens (CSS Variables)
The app uses HSL-based CSS variables for full theming support:
```
--primary          Main brand color
--secondary        Secondary actions
--muted            Subtle backgrounds
--accent           Highlights
--destructive      Errors & warnings
--sidebar-*        Sidebar-specific tokens
```

### Custom Animations
```
fade-in            Smooth entry (opacity + translateY, 0.4s)
accordion-down     Expand panels
accordion-up       Collapse panels
```

---

## 🌐 Localization

The app is built for **Arabic** as the primary language:
```html
<html lang="ar">
```

- RTL layout support via Tailwind
- Arabic title and meta description
- Designed for right-to-left reading flow

---

## 🧩 UI Components

Built on **shadcn/ui** — a collection of accessible, customizable React components. Components are configured via `components.json` and styled using Tailwind CSS variables.

Available component categories:
- Layout & Navigation (Sidebar)
- Forms & Inputs
- Feedback (Alerts, Toasts)
- Overlays (Dialogs, Popovers)
- Data Display (Cards, Accordion)

---

## 🧪 Testing

Tests are configured with **Vitest** — a fast Vite-native test runner compatible with the Jest API.

```bash
bun run test        # Run all tests
bun run test --ui   # Visual test UI
```

---

## 📦 Key Scripts

```json
{
  "dev":     "Start development server",
  "build":   "Build for production",
  "preview": "Preview production build",
  "test":    "Run unit tests",
  "lint":    "ESLint code check"
}
```

---

## 👤 Author

**Ashraf Mahmoud**
Computer Sciences — New Mansoura University

---

## 📄 License

This project is for educational purposes.
