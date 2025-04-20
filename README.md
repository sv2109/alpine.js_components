# Alpine.js Components Library with Tailwind CSS 🌟

This project is a collection of interactive components built using **Alpine.js** and styled with **Tailwind CSS**. It demonstrates how to create dynamic, responsive, and visually appealing UI elements with minimal JavaScript and modern CSS utilities.

🔗 **Live Demo**: [Alpine.js Components](https://sv2109.github.io/alpine.js_components/)

---

## 📦 Features

### 1. Dropdown Menu 📂
- A toggleable dropdown menu with smooth animations.
- Uses `x-data` for state management and `x-show` for conditional rendering.
- Includes `@click.outside` to close the menu when clicking outside.

### 2. Modal Dialog 🖼️
- A modal window with a backdrop overlay.
- Includes a title, body content, and footer with "Accept" and "Cancel" buttons.
- Uses `x-teleport` to render the modal at the root of the document for better accessibility.

### 3. Tabs Navigation 🗂️
- A tabbed interface with multiple sections (e.g., Home, Users, Settings).
- Dynamically updates the active tab using `x-data` and `x-show`.
- Styled with Tailwind's utility classes for a clean and modern look.

### 4. Image Carousel 🎠
- A responsive image carousel with navigation buttons.
- Allows users to navigate through images using `prev` and `next` methods.
- Includes a thumbnail preview with active state highlighting.

### 5. Accordion 📖
- A collapsible accordion with multiple sections.
- Uses `x-collapse` for smooth open/close animations.
- Dynamically updates the active section using `x-data`.

### 6. Notification Banner 🔔
- A dismissible notification banner with a progress bar.
- Automatically hides after a configurable timeout.
- Uses `x-init` and `$watch` for managing the timer and progress bar.

### 7. Popover Tooltip 💬
- A hover-activated popover with a title and message.
- Uses `x-show` for conditional rendering and `x-html` for rich content.

---

## 🛠️ Technologies Used

### **Alpine.js**
- **`x-data`**: Manages component state.
- **`x-show`**: Toggles visibility of elements.
- **`x-transition`**: Adds smooth animations.
- **`x-teleport`**: Moves elements to a different part of the DOM.
- **`x-collapse`**: Provides collapsible animations.
- **`@click` and `@mouseenter`**: Event listeners for user interactions.
- **`$watch`**: Observes changes in data and triggers actions.

### **Tailwind CSS**
- Utility-first CSS framework for rapid UI development.
- Custom components and utilities defined using `@layer` for buttons, scrollbars, and more.
- Responsive design and hover effects for better user experience.

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alpinejs_and_tailwindcss.git
   ```
2. Open the `index.html` file in your browser to explore the components.

---

## 🌐 Links
- **Live Demo**: [Alpine.js Components](https://sv2109.github.io/alpine.js_components/)
- **Alpine.js Documentation**: [https://alpinejs.dev](https://alpinejs.dev)
- **Tailwind CSS Documentation**: [https://tailwindcss.com](https://tailwindcss.com)

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
