
Built by https://www.blackbox.ai

---

```markdown
# BCP Edu College Login System

## Project Overview

The BCP Edu College Login System is a simple yet stylish web application that allows users to log into their educational platform, where they can choose and study various subjects. Built with HTML, CSS, and JavaScript, this application features a dynamic, user-friendly interface with rich animations and effects, enhanced by the Tailwind CSS framework and particles.js for an engaging background experience.

## Installation

To run the project locally, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   cd bcp-edu-college-login-system
   ```

2. Open the `index.html` file in your web browser. You can simply double-click the file or use a local server if you prefer.

## Usage

1. Open `index.html` in your browser.
2. Enter your username and password.
3. Click the "Log in" button to access the homepage.
4. From the homepage, select a subject to view the available lessons.
5. Use the appropriate buttons to navigate through lessons and mark them as completed.

## Features

- **User Login:** A simple login interface that redirects users to a subject selection page after a successful login.
- **Dynamic Subject Selection:** Users can choose from various subjects with attractive buttons.
- **Lesson Navigation:** Each subject page allows users to navigate through a series of lessons with 'Next' and 'Previous' controls.
- **Mark Lessons as Completed:** Users can mark lessons as completed or incomplete, with states saved in local storage.
- **Search Functionality:** A search bar to filter lessons based on user input.
- **Dark Mode Toggle:** Option to switch to dark mode for better accessibility and convenience.

## Dependencies

This project requires the following dependencies, which are linked in the HTML files:

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework used for styling.
- [Font Awesome](https://fontawesome.com/): Icons for various UI elements.
- [Particles.js](https://vincentgarreau.com/particles.js/): A customizable particles effect for the background.

## Project Structure

The project includes the following main files:

```
.
├── index.html        # The login page for the application.
├── homepage.html     # The main page after login showcasing subject options.
├── filipino.html     # A subject page that displays lessons for Filipino.
└── (Optional JS/CSS) # Link to styles and scripts like Tailwind CSS and Font Awesome are embedded in the HTML files.
```

### Additional Scripts
- JavaScript embedded in each HTML file for functionality such as:
  - User login processing.
  - Dynamic welcome messages.
  - Lesson management (navigate, mark as complete).
  - Dark mode functionality.

## License

This project is open-source and available under the MIT License. Feel free to contribute to the project or customize it for your use case. Enjoy learning and happy coding!
```