# Todo List App

A modern, feature-rich Todo List application built with React and Tailwind CSS.

## Features

- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Edit existing tasks
- ✅ Delete tasks
- ✅ Filter by All/Active/Completed
- ✅ Statistics dashboard showing total, active, and completed tasks
- ✅ Keyboard shortcuts (Enter to add/save, Escape to cancel editing)
- ✅ Beautiful gradient background
- ✅ Responsive design
- ✅ Smooth animations and transitions

## Prerequisites

Before you begin, ensure you have installed:
- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm (comes with Node.js)

## Installation

1. Navigate to the project directory:
```bash
cd todo-app
```

2. Install dependencies:
```bash
npm install
```

## Running the App

Start the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or another port if 5173 is busy).

## Building for Production

To create a production build:
```bash
npm run build
```

To preview the production build:
```bash
npm run preview
```

## Technologies Used

- **React** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Icon library

## Project Structure

```
todo-app/
├── src/
│   ├── App.jsx          # Main App component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles with Tailwind directives
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── vite.config.js       # Vite configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── postcss.config.js    # PostCSS configuration
```

## Usage

- **Add a task**: Type in the input field and press Enter or click the Add button
- **Complete a task**: Click the checkbox next to the task
- **Edit a task**: Click the edit icon, modify the text, and press Enter or click the save icon
- **Delete a task**: Click the trash icon
- **Filter tasks**: Use the All/Active/Completed buttons to filter your view

## License

This project is open source and available under the MIT License.
