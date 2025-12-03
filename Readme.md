# Portfolio Project

A modern, responsive portfolio website built with HTML, CSS, and Tailwind CSS. This project showcases a professional portfolio with multiple sections including hero, about, projects, skills, and contact information.

## Project Structure

```
portfolio/
├── assets/
│   ├── orchard.png
│   ├── portv1.png
│   ├── profile.png
│   └── sentiment.png
├── node_modules/
├── src/
│   ├── index.html
│   ├── input.css
│   └── output.css
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

## Prerequisites

Before running this project, ensure you have the following installed:

- **Node.js** (version 14 or higher) - [Download here](https://nodejs.org/)
- **npm** (comes with Node.js)

## Installation & Setup

Follow these steps to set up and run the project:

### 1. Clone or Download the Project

```bash
cd portfolio
```

### 2. Install Dependencies

Install the Tailwind CSS CLI and other dependencies:

```bash
npm install 
npm install tailwindcss @tailwindcss/cli
```

### 3. Run Tailwind CSS Watcher

To compile CSS files and watch for changes, run:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

This command will:
- **-i ./src/input.css**: Input CSS file containing Tailwind directives
- **-o ./src/output.css**: Output compiled CSS file
- **--watch**: Automatically recompile when changes are detected

### 4. Open the Project

Open `index.html` in your web browser:
- Double-click the `index.html` file, or
- Use a local server (recommended):

Then visit `http://localhost:XXXX` in your browser.

## CSS Techniques Used

This project utilizes various Tailwind CSS utilities and CSS techniques to create a responsive, modern design:

### 1. **Responsive Design**
### 2. **Flexbox Layout**
### 3. **Grid System**
### 4. **Spacing Utilities**
### 5. **Typography**
### 6. **Colors & Backgrounds**
### 7. **Border & Corner Styling**
### 8. **Shadows & Elevation**
### 9. **Transforms & Transitions**
### 10. **Animations**
### 11. **Visibility & Display**
### 12. **Interactive States**
### 13. **Custom CSS**

## File Structure Details

- **index.html**: Main HTML file containing the complete portfolio structure
- **src/input.css**: Source CSS file with Tailwind directives (@tailwind, @layer, @apply)
- **src/output.css**: Compiled CSS file (auto-generated, don't edit manually)
- **assets/**: Folder containing images used in the portfolio
- **.gitignore**: Specifies files to ignore in version control
- **package.json**: Project dependencies and scripts configuration

## Troubleshooting

**Styles not appearing?**
- Ensure the watch command is running
- Check that output.css is linked in index.html: `<link rel="stylesheet" href="./src/output.css">`
- Clear browser cache (Ctrl+Shift+Delete)


**Node.js not found?**
- Download and install from [nodejs.org](https://nodejs.org/)

## Resources

- [Tailwind CSS Documentation](https://tailwindcss.com/)
- [Tailwind CLI Guide](https://tailwindcss.com/docs/installation)

---

**Happy Coding!** 🚀