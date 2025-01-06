## 🌐 [English Version of README](README_EN.md)

# Web Programmer - IFRS

This project is part of the **Web Programmer Course** at **IFRS** (Instituto Federal de Educação, Ciência e Tecnologia), gathering various code examples in **HTML**, **CSS**, and **JavaScript**. The directory structure is organized by topics and dates, offering examples for different functionalities, from basic media inclusion to more advanced scripts for user interaction.

## 🔨 Project Features

- **HTML Examples:**

    - Inserting images, audio, and video
    - Creating basic and advanced forms
    - Using basic HTML5 semantics

- **CSS Examples:**

    - Styling pages and menus
    - Using Media Queries for responsiveness
    - Customizing elements (hover effects, submenus, etc.)

- **JavaScript Examples:**

    - Event handling (onLoad, onClick, mouse events)
    - Form validation and required fields
    - Mathematical calculations (averages, BMI, loops)
    - Text transformations (uppercase, lowercase, etc.)

## ✔️ Tools and Technologies Used

- **HTML5** for semantic page structure
- **CSS3** for design, responsiveness, and advanced styling
- **JavaScript** for adding interactivity and dynamism to pages
- **SweetAlert** (included in `sweetalert-master/`) as a library for creating styled alerts
- **Git** for version control, enabling backups and sharing

## 📁 Project Structure

Below is a summary of the main folders and their contents:

- **1.11.1 Exemplo imagem.html-20241231/**

    - `imagem.html`: Example of using the `<img>` tag.
    - `esquilo.jpg`: Image displayed in the example.

- **1.12.1 Exemplo audio.html-20241231/**

    - `audio.html`: Example of using the `<audio>` tag.
    - `music.mp3`: Audio file.

- **2.7.1 Exemplo menu-20250103/**

    - `index.html`: Example of an interactive menu with CSS.
    - `styles.css`: Menu styles (hover effects, submenus, etc.).

- **2.8.1 Exemplo Media Query-20250103/**

    - `index.html`: Using different breakpoints for responsive layout.
    - `pagina.css`: Contains the Media Queries.

- **4.12.1 Código-fonte onLoad-20250104/**

    - `load.html`: Demonstrates `onLoad` and `onResize` events.
    - `load.js`: Script for logging events on the page.

- **4.16.1 Código-fonte validação de formulários-20250104/**

    - `vazio.html`: Demonstrates a simple empty field check.
    - `vazio.js`: Code that alerts if the field is empty.

- **Backup/**

    - Zips of each topic, in case you want to restore or download them separately.

- **sweetalert-master/**

    - Contains the source code of the SweetAlert library, including examples, styles, tests, and documentation.
    - Useful for displaying friendly and customized alerts in JavaScript.

## 🛠️ How to Run the Project

This set of examples does not necessarily require Node.js. You can open the `.html` files directly in your browser. However, if you wish to use a local server or additional scripts, follow the instructions below:

1. **Ensure Node.js is installed (optional)**\
   To check, run the following command in your terminal:

   ```bash
   node -v
   ```

   If not installed, download it from the [official Node.js website](https://nodejs.org/).

2. **Clone the Repository**\
   Copy the repository URL and run the following command in your terminal:

   ```bash
   git clone <REPOSITORY_URL>
   ```

3. **Open the files in your browser**\
   Navigate to the folder of the example you want to test and open the `.html` file.

    - Example: `1.11.1 Exemplo imagem.html-20241231/imagem.html`.

   **Optional**: Run a local server:

   ```bash
   npx http-server .
   ```

   Then access `http://localhost:8080` (or the configured port) in your browser.

## 🌐 Deployment

To publish these examples, you can:

- **Use a static hosting service:**

    - Examples include [GitHub Pages](https://pages.github.com/), [Vercel](https://vercel.com/), or [Netlify](https://www.netlify.com/).
    - Simply upload the `.html`, `.css`, `.js` files, and assets (images, audio, videos) to the chosen service.

- **Set up a web server** (Nginx, Apache, etc.):

    - Upload the project files to a VPS or cloud instance (AWS, Azure, DigitalOcean, etc.) and point the server to the folder containing the project.
    - From there, access the configured address (e.g., `www.yoursite.com`).

This README serves as a guide to understanding the overall structure and how to run each example. Explore the folders, open the `.html` files, and practically learn different concepts of Web development!

