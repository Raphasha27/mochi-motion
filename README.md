# 🏛️ KIROV DYNAMICS | MOCHI MOTION (v1.0)

[![Kirov Dynamics](https://img.shields.io/badge/Kirov_Dynamics-Sovereign_Intelligence-002D62?style=for-the-badge&labelColor=0d1117)](https://github.com/Raphasha27)
![Status](https://img.shields.io/badge/Status-🚀_Active-3fb950?style=for-the-badge&labelColor=0d1117)

> **"Professional Motion Physics for the Modern Web."**

<img width="1800" height="1200" alt="IMG_0349" src="https://github.com/user-attachments/assets/d9e5a102-e3ae-455f-9a57-95fa8c13fe92" />

---
**Mochi Motion** brings world-class animation to your React applications with zero configuration. Built on Framer Motion with intelligent defaults, it delivers the smooth, bouncy animations you see in the best modern web apps. Re-engineered as a high-performance animation asset within the **Kirov Dynamics** design system.

## ✨ Why Mochi Motion?

**It just works.** Drop it in your React or Next.js app and get beautiful animations instantly. No complex configuration, no performance headaches, no framework lock-in.

- **Universal compatibility** — Works with React, Next.js App Router, Pages Router, Vite, and Create React App
- **Professional spring physics** — Four carefully tuned presets plus full customization
- **Performance optimized** — Intersection Observer API with smart defaults
- **TypeScript native** — Written in TypeScript with comprehensive type definitions
- **Production ready** — 8KB compressed, battle-tested in real applications

## 📦 Installation

```bash
npm install mochi-motion framer-motion react-intersection-observer
```

## 🚀 Quick Start

### React (Vite, CRA, or any React app)

```tsx
import { ReactTransition, RevealOnScroll } from 'mochi-motion'

function App() {
  return (
    <ReactTransition>
      <RevealOnScroll effect="fade-up">
        <h1>Welcome to the future</h1>
      </RevealOnScroll>
    </ReactTransition>
  )
}
```

### Next.js App Router

```tsx
// app/layout.tsx
import { AppRouterTransition } from 'mochi-motion'

export default function RootLayout({ children }) {
  return (
    <html>
      <body>
        <AppRouterTransition>
          {children}
        </AppRouterTransition>
      </body>
    </html>
  )
}
```

## ⚙️ Spring Physics

The magic happens in the spring configurations. We've spent months tuning these presets to feel just right in real applications.

### Gentle
Soft, premium feel. Perfect for luxury brands and professional interfaces.
```tsx
<RevealOnScroll preset="gentle">
  <Card>Elegant and refined</Card>
</RevealOnScroll>
```

### Wobbly  
Bouncy and engaging. Adds personality without being distracting.
```tsx
<RevealOnScroll preset="wobbly">
  <Button>Fun and interactive</Button>
</RevealOnScroll>
```

### Stiff
Quick and responsive. Great for dashboards and productivity apps.
```tsx
<RevealOnScroll preset="stiff">
  <MenuItem>Snappy and efficient</MenuItem>
</RevealOnScroll>
```

---
*Developed by Raphasha27 - Kirov Dynamics 2026.*

