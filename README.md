# React State Management Project Series

A comprehensive project series demonstrating different approaches to state management in React applications through an interactive counter application.

## Project Description

This project series progressively implements state management solutions, starting with React's built-in `useState` hook and advancing to Context API and Redux. Each implementation showcases how to share state across components and maintain application-wide data consistency.

## Learning Objectives

By completing these projects, you will:

- Understand fundamental React state management using `useState`
- Learn to implement global state management with Context API
- Master Redux for complex state management scenarios
- Compare different state management solutions
- Implement state persistence across components
- Understand the concept of single source of truth
- Learn to structure applications for scalable state management

## Requirements

### Technical Requirements
- **Node.js** (v14 or later)
- **npm** or **yarn** package manager
- **React** (v18 or later)
- **TypeScript**
- **Next.js** framework
- **Redux Toolkit** (for Redux implementation)
- **React-Redux** bindings

### Development Environment
- Code editor (VS Code recommended)
- Terminal/command line access
- Modern web browser (Chrome, Firefox, or Edge)

## Project Structure

```
├── pages/
│   └── counter-app.tsx          # Main counter application
├── components/                  # Reusable UI components
├── layouts/
│   └── Header.tsx              # Shared header component
├── context/                    # Context API version (0x05)
│   └── CountContext.tsx
├── store/                      # Redux version (0x06)
│   └── store.ts
└── README.md
```

## Implementation Variants

### 0x04: useState Version
Simple state management within a single component

### 0x05: Context API Version
- `context/CountContext.tsx`: Context provider and hooks
- Modified `_app.tsx` to wrap application with provider

### 0x06: Redux Version
- `store/store.ts`: Redux store configuration
- Updated components to use Redux hooks

## Expected Outcomes

After completing all versions, you will have:

1. A working counter application with three different state management implementations
2. Understanding of when to use each state management solution
3. Practical experience with modern React state management patterns
4. A foundation for building more complex stateful applications
5. Ability to make informed decisions about state management in your projects

## Important Note

While copying and pasting code may seem quick and convenient, it often hinders true understanding. To get the most out of this learning experience:

- Carefully read and understand the instructions for each task
- Type the code yourself to internalize the logic and structure
- Experiment and test your code to see how it works in practice

**Hands-on practice leads to deeper learning and long-term retention. Keep coding!**