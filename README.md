# Linux World

> **Explore. Learn. Master Linux.**

Linux World is a modern desktop-first web dashboard built with **HTML5**, **CSS3**, and **Vanilla JavaScript**.

The goal of this project is to provide an interactive environment for exploring Linux distributions, learning Linux commands, installing popular software, and understanding different package managers through a beautiful and responsive user interface.

---

# Preview

> Linux World Dashboard (Version 1)

- Modern Dashboard UI
- Interactive Distribution Explorer
- Software Installer
- Command Reference
- Installation Terminal
- Theme Switcher

---

# Goals

This project is designed to:

- Learn modern HTML5
- Master CSS architecture
- Write modular Vanilla JavaScript
- Practice Software Engineering principles
- Build a professional GitHub portfolio project

---

# Features

## Version 1

### Dashboard

- Desktop-first layout
- Sidebar navigation
- Top search bar
- Theme switcher

### Linux Explorer

- Distribution information
- Distribution details
- Official website
- Download links

### Software Installer

- Popular software list
- Installation commands
- Copy command
- Package manager support

### Terminal

- Interactive installation terminal
- Command preview

### Commands

- Essential Linux commands
- Categorized command cards

---

# Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- JSON
- Clipboard API
- LocalStorage

---

# Software Architecture

Linux World follows a **Layer-Based Architecture**.

```
                User
                  │
                  ▼
             index.html
                  │
      ┌───────────┴───────────┐
      ▼                       ▼
     CSS                  JavaScript
      │                       │
      ▼                       ▼
 User Interface        Application Logic
                              │
                              ▼
                         JSON Data
                              │
                              ▼
                     Dynamic UI Rendering
```

The application separates:

- Structure
- Presentation
- Behavior
- Data

This separation improves maintainability, readability, and scalability.

---

# Project Structure

```text
linux-world/
│
├── index.html
│
├── assets/
│   ├── fonts/
│   ├── icons/
│   └── images/
│
├── css/
│   ├── reset.css
│   ├── variables.css
│   ├── typography.css
│   ├── layout.css
│   ├── utilities.css
│   ├── main.css
│   └── components/
│       ├── sidebar.css
│       ├── topbar.css
│       ├── hero.css
│       ├── tabs.css
│       ├── software.css
│       ├── terminal.css
│       ├── analyzer.css
│       ├── commands.css
│       ├── cards.css
│       └── footer.css
│
├── js/
│   ├── main.js
│   ├── modules/
│   │   ├── sidebar.js
│   │   ├── topbar.js
│   │   ├── hero.js
│   │   ├── tabs.js
│   │   ├── software.js
│   │   ├── terminal.js
│   │   ├── analyzer.js
│   │   ├── commands.js
│   │   ├── search.js
│   │   └── theme.js
│   │
│   └── utils/
│       ├── dom.js
│       ├── clipboard.js
│       ├── storage.js
│       └── helpers.js
│
├── data/
│   ├── distros.json
│   ├── software.json
│   └── commands.json
│
├── README.md
└── LICENSE
```

---

# Data Model

Linux World is a data-driven application.

The interface is generated from JSON files instead of hardcoded content.

Core entities:

- Distribution
- Package Manager
- Software
- Linux Command

---

# Version Roadmap

## Version 1

- Sidebar
- Search
- Hero Section
- Distribution Explorer
- Software Installer
- Hardware Analyzer
- Popular Software
- Installation Terminal
- Essential Commands
- Theme Switcher
- Footer

---

## Version 2

Planned features:

- Compare Distributions
- Terminal Playground
- Learning Path
- Favorites

---

## Version 3

Future goals:

- Backend API
- User Accounts
- Authentication
- Cloud Sync
- Bookmarks
- Progressive Web App

---

# Design Principles

Linux World follows several software engineering principles:

- Separation of Concerns
- Single Responsibility Principle
- Modular Design
- Data-Driven UI
- Component-Based Styling

---

# Future Refactoring

Version 1 uses a Layer-Based Architecture.

Future versions will migrate to a Feature-Based Architecture for better scalability.

---

# License

MIT License
