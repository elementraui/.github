# Elementra UI

<div>
  
  Your Building Blocks for Modern UIs
  
  [![npm version](https://img.shields.io/npm/v/elementra-ui.svg)](https://www.npmjs.com/package/elementra-ui)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Downloads](https://img.shields.io/npm/dm/elementra-ui.svg)](https://www.npmjs.com/package/elementra-ui)
  
</div>

## Overview

Elementra UI is a modern, reusable component library designed to simplify your workflow and accelerate the development of stunning, accessible, and responsive user interfaces. Built with **React.js**, **Next.js**, **Tailwind CSS**, and **Framer Motion**, Elementra empowers developers to craft beautiful UIs with ease.

## Features ✨

- 🎨 **Modern Design**: Beautiful, consistent components following modern design principles
- 📱 **Responsive**: Fully responsive components that work across all devices
- ♿ **Accessible**: Built with accessibility in mind, following WAI-ARIA standards
- 🎭 **Animations**: Smooth animations powered by Framer Motion
- 🔧 **JavaScript-Based**: Built with vanilla JavaScript for maximum compatibility
- 🎨 **Customizable**: Easy theming and style customization with Tailwind CSS

## Available Components 🧱

- 🔘 Button
- 🎯 Alert
- 🏷️ Badge
- 💳 Card
- 🖼️ Modal
- 📊 Progress
- 📝 Select
- 🔄 Switch
- 📑 Tabs
- 🍞 Toast
- ... and more coming soon!

## Installation 📦

You can install Elementra UI using either npm or GitHub Packages:

```bash
# Using npm
npm install elementra-ui

# Using GitHub Packages
npm install @waleedcodes/elementra-ui
```

## Quick Start 🚀

1. Install required dependencies:

```bash
npm install clsx tailwind-merge
```

2. Add components using the CLI:

```bash
npx elementra-ui add
```

Select components using the up/down arrow keys. Press spacebar to select multiple components, then press enter to add them to your src folder.

3. Import and use components:

```jsx
import { Button } from "@/components/ui/button";

export default function App() {
  return <Button variant="default">Click me</Button>;
}
```

## Tailwind CSS Configuration 🎨

Add this to your **tailwind.config.js**:

```js
module.exports = {
  content: ["./src/components/**/*.{js,jsx}"],
  plugins: [require("tailwindcss-animate")],
};
```

## Documentation 📖

Visit our [documentation website](https://elementra-ui.vercel.app/docs/) for:

- 📚 Component API references
- 💡 Interactive examples
- 🎨 Theme customization
- ⚡ Best practices
- 🔄 Migration guides

## Community & Support 💬

- 💬 [GitHub Discussions](https://github.com/elementra-ui/discussions)
- 📺 [YouTube Channel](https://youtube.com/@waleedcodes)
- 🐦 [Twitter](https://twitter.com/waleedcodes)
- 📝 [Blog](https://elementra-ui.vercel.app/blog)

<div>
  Made with ❤️ by <a href="https://github.com/waleedcodes">@waleedcodes</a> © 2025 Elementra UI. All rights reserved.
</div>
