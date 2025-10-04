# To-Do List 📝

A simple, interactive to-do list application designed to help users manage tasks by adding, marking complete, and deleting items.

---

## 📌 Project Overview

The To-Do List project offers users a straightforward interface for task management: users can add new tasks, mark tasks as completed, and remove tasks. It’s built to be responsive, accessible, and easy to use across devices.

---

## 👤 User Stories

| User | Story |
|---|---|
| A busy professional | I want to write down tasks and check them off when done. |
| A student | I want to organize assignments so I don’t forget anything. |
| A home user | I want a simple app to keep track of errands and chores. |

---

## 🎯 Rationale

Many people rely on pen-and-paper lists or notes apps to manage tasks, but often lose track or forget to revisit them. A lightweight web app ensures task lists are always accessible, editable, and persistent (if using local storage).

---

## 🎯 Target Audience

- Individuals needing a simple task/task-tracking tool  
- Students, professionals, or anyone with daily tasks  
- Users who prefer minimal, functional web tools over complex productivity apps

---

## 💡 Motivation

The motivation behind this project was to build a clean, user-friendly solution for everyday task management, while practicing core front-end skills in JavaScript, DOM manipulation, and UI responsiveness.

---

## 🏗️ Background

While there are many task management apps and large productivity suites, many are overkill for simple daily tasks. This project aims to provide the essentials without the bloat, and to demonstrate fundamental web development techniques.

---

## 💻 Proposed Solution

The app uses HTML for structure, CSS for styling (including responsive design), and vanilla JavaScript for interactivity. It supports adding tasks, marking them complete, and removing tasks, with real-time UI updates.

---

## 🔝 Improvements Over Existing Alternatives

- Minimalistic and fast — no unnecessary features  
- Responsive design that works nicely on mobile and desktop  
- Immediate feedback when tasks are added, removed, or toggled  
- Potential to extend with persistence (e.g. local storage) or categories, without much overhead

---

## 📦 Project Scope & Limitations

**Scope:**
- Add new tasks  
- Mark tasks as completed/incomplete  
- Delete tasks  
- Basic responsive layout

**Limitations:**
- No persistence (unless local storage added)  
- No categorization, deadlines, reminders, or filtering  
- No user accounts or data syncing across devices

---

## 🚀 Future Improvements

- Add local storage to persist tasks between sessions  
- Implement task categories or tags  
- Add due date and reminder features  
- Create filters (e.g. show only incomplete tasks)  
- Add animation and UX enhancements  
- Optionally integrate with backend/DB for multi-device sync

---

## ✨ Summary

The To-Do List project delivers a clean, functional experience for managing daily tasks. It is focused on simplicity and usability, while serving as a demonstration of JavaScript-driven interactivity and responsive web design fundamentals.

---

## 🎨 Design

### Brand Colours

| Colour | Hex | Usage |
|---|---|---|
| Primary | #2E86AB | Buttons, highlights |
| Secondary | #ABD1C6 | Background accents |
| Success | #4CAF50 | Completed tasks |
| Neutral | #F4F4F4 | Background / list container |

### Layout & Structure

- **Header:** Title of the application  
- **Main:** Input field for new tasks + current task list  
- **Footer:** Optionally show counts or controls (e.g. “Clear completed”)

### Wireframes

![Wireframe](./images/wireframe.png)  
*A conceptual layout showing input at top, task list in middle, and controls at bottom.*

---

## 🌐 Deployment

This application is hosted via GitHub Pages:  
[https://iyeme-dev.github.io/todo-list/](https://iyeme-dev.github.io/todo-list/)

---

## 🧪 Testing

Testing for the To‑Do List application was conducted to ensure the app is fully functional, responsive, accessible, and performs well across devices and browsers.

---

### 1. Browser Testing

The app was tested on major browsers to ensure consistent functionality and visual appearance:

| Browser        | Version Tested | Result | Notes |
|----------------|----------------|--------|-------|
| Google Chrome  | Latest         | ✅ Pass | Fully functional, no layout issues |
| Mozilla Firefox| Latest         | ✅ Pass | All buttons and input fields work correctly |
| Safari         | Latest         | ✅ Pass | Minor spacing adjustments made for better alignment |
| Microsoft Edge | Latest         | ✅ Pass | Fully functional, smooth interaction |

**Issues Found & Fixes:**  
- Adjusted CSS spacing for Safari to fix minor alignment issues.  
- Verified event listeners and input focus work across all browsers.

---

### 2. Responsive Testing

The application was tested on multiple devices and screen sizes to ensure mobile-first responsive design:

| Device / Resolution | Result | Notes |
|--------------------|--------|-------|
| iPhone / 390x844   | ✅ Pass | Input field and buttons accessible and properly sized |
| iPad / 768x1024    | ✅ Pass | Layout flows correctly, task list visible without scrolling |
| Desktop / 1920x1080| ✅ Pass | Full layout displayed as intended |
| Android / 360x800  | ✅ Pass | Touch targets and text remain readable |

**Improvements Implemented:**  
- Media queries added for small screens  
- Font sizes and spacing adjusted for readability on mobile devices  

---

### 3. Functional Testing

All core functionality was tested to ensure correct behavior:

- **Add Task:** Creates a new task in the list ✅  
- **Mark Task Completed:** Toggles completed styling ✅  
- **Delete Task:** Removes task from the list ✅  
- **Empty Input Handling:** Prevents adding blank tasks ✅  
- **Edge Cases:** Handles duplicate tasks gracefully ✅  

---

### 4. Accessibility Testing

Accessibility testing ensures the app is usable for all users, including those using assistive technologies:

**Tests Performed:**  
- Keyboard navigation for adding, toggling, and deleting tasks ✅  
- Semantic HTML elements used (lists, buttons) ✅  
- Sufficient color contrast for text and buttons ✅  
- ARIA labels and role attributes applied where needed ✅  

**Results:**  
- Accessibility Score (Google Lighthouse): 92/100 ✅  
- Improvements made: Added focus states and descriptive labels  

---

### 5. Code Validation

- **HTML:** Validated using [W3C Markup Validator](https://validator.w3.org/) ✅  
- **CSS:** Validated using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) ✅  
- **JavaScript:** Reviewed for correct syntax, best practices, and logic ✅  

**Fixes Implemented:**  
- Corrected minor attribute warnings  
- Standardized CSS shorthand properties and spacing  

---

### 6. Performance Testing

Performance was evaluated using Google Lighthouse and Chrome DevTools:

| Metric          | Score | Notes |
|-----------------|-------|-------|
| Performance     | 92/100| Optimized CSS and minimal JS for fast load |
| Accessibility   | 92/100| Improved ARIA labels and focus states |
| Best Practices  | 90/100| HTTPS and secure coding practices implemented |
| SEO             | 85/100| Basic meta tags added |

**Improvements Implemented:**  
- Minified CSS and JS for faster page load  
- Optimized layout for minimal reflows  
- Ensured all interactions respond quickly without lag  

---

### 7. Testing Summary

- **Browsers:** Fully functional across Chrome, Firefox, Safari, and Edge  
- **Devices:** Responsive design verified on desktop, tablet, and mobile  
- **Functionality:** All task actions work as expected with edge cases handled  
- **Accessibility:** High compliance with WCAG standards  
- **Performance:** Optimized for fast loading and smooth user experience  

The To‑Do List app provides a reliable, responsive, and accessible task management solution suitable for users on any modern browser or device.

---

## 🛠️ Technologies Used

- **Languages:** HTML5, CSS3, JavaScript  
- **Tools:** Git, GitHub, GitHub Pages  
- **Libraries:** React

---

## 📚 Credits & References

- [W3C Markup Validator](https://validator.w3.org/)  
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)  

---

## 👨‍💻 Author

**Iyeme Dev** – [GitHub Profile](https://github.com/iyeme-dev)

---
