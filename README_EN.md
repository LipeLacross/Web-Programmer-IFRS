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

Below is a complete summary of all the folders and their contents:

- **1.11.1 Exemplo imagem.html-20241231/**
    - `imagem.html`: Example of using the `<img>` tag.
    - `esquilo.jpg`: Image displayed in the example.

- **1.12.1 Exemplo audio.html-20241231/**
    - `audio.html`: Example of using the `<audio>` tag.
    - `music.mp3`: Audio file.

- **1.12.2 Exemplo video.html-20241231/**
    - `video.html`: Example of using the `<video>` tag.
    - `video.mp4`: Video file.

- **2.1.1 Exemplo 1-20241231/**
    - `index.html`: Basic example with inline styles.
    - `estilo.css`: Demonstrates CSS styling.

- **2.7.1 Exemplo menu-20250103/**
    - `index.html`: Example of an interactive menu with CSS.
    - `styles.css`: Menu styles (hover effects, submenus, etc.).

- **2.8.1 Exemplo Media Query-20250103/**
    - `index.html`: Using different breakpoints for responsive layout.
    - `pagina.css`: Contains the Media Queries.

- **4.12.1 Código-fonte onLoad-20250104/**
    - `load.html`: Demonstrates `onLoad` and `onResize` events.
    - `load.js`: Script for logging events on the page.

- **4.13.1 Código-fonte onClick-20250104/**
    - `click.html`: Example for handling click and double-click events.
    - `click.js`: Script to handle image toggling based on click events.
    - `fachada.jpg`: Image displayed on click.
    - `ifrs.gif`: Image displayed on double-click.

- **4.15.1 Código-fonte eventos do mouse-20250104/**
    - `mouse.html`: Example of mouse events like hover, click, and drag.
    - `mouse.js`: Script demonstrating color changes during mouse events.
    - `mouse.css`: Styles for the mouse interaction example.

- **4.16.1 Código-fonte validação de formulários-20250104/**
    - `vazio.html`: Demonstrates a simple empty field check.
    - `vazio.js`: Code that alerts if the field is empty.

- **4.17.1 Código-fonte cálculo do IMC-20250104/**
    - `imc.html`: Page for calculating BMI.
    - `imc.js`: Script to compute BMI and validate input fields.

- **4.18.1 Código-fonte transformação de letra-20250104/**
    - `maiuscula.html`: Example for converting text to uppercase.
    - `maiuscula.js`: Script to automatically transform text input.

- **4.3.1 Código-fonte operações aritméticas-20250104/**
    - `indexjs.html`: Example using basic arithmetic operations.
    - `meucodigo.js`: Script demonstrating prompts and calculations.

- **4.5.1 Código-fonte média de valores-20250104/**
    - `media.html`: Example for calculating average grades.
    - `media.js`: Script for grade calculation with conditions.

- **4.6.1 Código-fonte confirmação-20250104/**
    - `confirm.html`: Example demonstrating the `confirm` method.
    - `confirm.js`: Script to handle confirmation prompts.

- **4.7.1 Código-fonte laços de repetição-20250104/**
    - `repete.html`: Example demonstrating loops.
    - `repete.js`: Script to iterate and display messages.

- **4.8.1 Código-fonte para até-20250104/**
    - `parate10.html`: Example using loops to list even numbers.
    - `parate10.js`: Script to generate even numbers up to a limit.

- **Backup/**
    - Contains ZIP files for each example folder.

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

