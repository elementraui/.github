# Elementra

Your Building Blocks for Modern UIs

[![npm version](https://img.shields.io/npm/v/elementra-ui.svg)](https://www.npmjs.com/package/elementra-ui)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Downloads](https://img.shields.io/npm/dm/elementra-ui.svg)](https://www.npmjs.com/package/elementra-ui)

</div>

## Overview

Elementra is a modern, reusable component library designed to simplify your workflow and accelerate the development of stunning, accessible, and responsive user interfaces. Built with **React.js**, **Tailwind CSS**, and **Framer Motion**, Elementra empowers developers to craft beautiful UIs with ease.

## Features 🚀

- **Customizable Components**: Tailor components to fit your brand and design system effortlessly
- **Theming Support**: Light, dark, and custom themes out-of-the-box
- **Built-in Animations**: Smooth, high-performance animations powered by Framer Motion
- **Accessibility First**: Designed to meet modern accessibility standards
- **Lightweight & Performant**: Minimal dependencies, maximum efficiency

## Installation 📦

Install Elementra using your preferred package manager:

```bash
# Using npm
npm install elementra-ui

# Using yarn
yarn add elementra-ui

# Using pnpm
pnpm add elementra-ui
```

## Quick Start 💻

```jsx
import { Button, Modal } from "elementra";

export default function App() {
  return (
    <div>
      <Button variant="primary">Click Me</Button>

      <Modal isOpen={true} onClose={() => console.log("Closed!")}>
        <h1>Welcome to Elementra!</h1>
      </Modal>
    </div>
  );
}
```

## Component Library 🛠️

### TextInput

A simple input field component.

#### Props:

- `placeholder` (string): Text to display when the input is empty.
- `value` (string): Controlled value of the input.
- `onChange` (function): Callback triggered when the input value changes.

#### Usage:

````jsx
<TextInput
  placeholder="Enter your name"
  value={name}
  onChange={(e) => setName(e.target.value)}
/>
<div align="center">


### Core Components

- **Buttons**
  - Primary, secondary, outlined variants
  - Loading states
  - Icon support

- **Modals**
  - Configurable animations
  - Multiple sizes
  - Custom positioning

- **Cards**
  - Flexible layouts
  - Header/footer support
  - Hover effects

- **Forms**
  - Input fields
  - Checkboxes
  - Radio buttons
  - Switches
  - Select menus


## Documentation 📖

Visit our [documentation website](https://elementraui.com) for:
- Detailed API references
- Interactive examples
- Theme customization guides
- Best practices
- Migration guides


## Contributing 🤝

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details on:

1. Setting up the development environment
2. Submitting pull requests
3. Code style guidelines
4. Bug reporting process

## Community & Support 💬

- 📫 [GitHub Discussions](https://github.com/elementra/discussions)
- 🐦 [Twitter @ElementraUI](https://twitter.com/ElementraUI)
- 📺 [YouTube Channel](https://youtube.com/@waleedcodes)
- 💬 [Discord Community](https://discord.gg/elementra)

## License 📄

Elementra is open-source software licensed under the [MIT License](LICENSE).

## Stay Connected 🌐

- Website: [www.elementraui.com](https://www.elementraui.com)
- Twitter: [@ElementraUI](https://twitter.com/ElementraUI)
- YouTube: [WaleedCodes](https://youtube.com/@waleedcodes)

---

<div align="center">
  Made with ❤️ by the Elementra Team @waleecodes
</div>
