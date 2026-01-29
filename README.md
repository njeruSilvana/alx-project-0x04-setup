# ALX React State Management Projects

This repository contains three Next.js projects demonstrating different state management approaches in React.

## Projects Overview

### 1. alx-project-0x04 - useState Hook
A counter application using React's built-in `useState` hook for local state management.

**Features:**
- Simple increment/decrement counter
- Local component state
- Colorful gradient UI

**Key Files:**
- `pages/counter-app.tsx`

---

### 2. alx-project-0x05 - Context API
Enhanced counter application using React Context API for global state management.

**Features:**
- Global state accessible across components
- Counter displayed in both Header and Counter page
- No prop drilling

**Key Files:**
- `context/CountContext.tsx` - Context provider and hook
- `pages/_app.tsx` - Wraps app with CountProvider
- `components/layouts/Header.tsx` - Displays counter from context
- `pages/counter-app.tsx` - Uses context hook

---

### 3. alx-project-0x06 - Redux Toolkit
Advanced counter application using Redux Toolkit for enterprise-level state management.

**Features:**
- Centralized Redux store
- Type-safe state management
- Action dispatching with Redux
- Counter synced across components

**Key Files:**
- `store/store.ts` - Redux store, slice, and actions
- `pages/_app.tsx` - Wraps app with Redux Provider
- `components/layouts/Header.tsx` - Reads from Redux store
- `pages/counter-app.tsx` - Dispatches Redux actions

---

## Installation & Running

For each project:
```bash
cd alx-project-0x0[4/5/6]
npm install
npm run dev -- -p 3000
```

Then visit: `http://localhost:3000/counter-app`

---

## Technologies Used

- Next.js 14+
- TypeScript
- React 18+
- Tailwind CSS
- Redux Toolkit (project 0x06 only)

---

## Learning Outcomes

- Understanding local vs global state
- Comparing useState, Context API, and Redux
- When to use each state management approach
- Type-safe state management in TypeScript

---

## Author

ALX Software Engineering Student

## Repository

GitHub: [alx-project-0x04-setup](https://github.com/njeruSilvana/alx-project-0x04-setup)
