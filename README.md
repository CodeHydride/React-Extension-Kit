# React Extension Starter Kit

A starter project to build a browser extension using React, powered by Vite for a fast and efficient development workflow. This setup is compatible with Chrome's Manifest V3 for browser extensions.

## Features
- **React** for building interactive UI components
- **Vite** for optimized and fast development setup
- **Manifest V3** compatibility, including background service workers and content scripts

## Getting Started

### 1. Setup React with Vite

To create your project using Vite, run the following commands:

```bash
npm create vite@latest my-extension -- --template react
cd my-extension
npm install
```

### 2. Project Structure

The project is organized to support a browser extension with all essential files:

```plaintext
my-extension
├── public
│   ├── manifest.json         # Extension settings and permissions
│   └── icon.png              # Extension icon (optional)
├── src
│   ├── background.js         # Background script
│   ├── content.js            # Content script
│   └── App.jsx               # App Component
│   └── main.jsx              # Entry point for React
├── index.html                # Popup HTML
├── vite.config.js            # Vite configuration
└── package.json              # Project metadata and dependencies
```
