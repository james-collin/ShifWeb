# Project Name

Chemical Project

## 🚀 Project Setup

Follow the steps below to set up and run the project locally.

### 📂 Folder Structure

```
project-root/
│── assets/
│   ├── fonts/
│   ├── icons/
│   ├── images/
│── css/
│   ├── input.css
│   ├── styles.css
│── .gitignore
│── .prettierrc
│── about.html
│── contact.html
│── index.html
│── insight-navigator.html
│── services.html
│── tailwindcss.exe
```

## 🛠️ Setup Instructions

### Install Tailwind CSS Standalone CLI

Since you are using the **standalone CLI version**, you do not need npm. The Tailwind CLI binary (`tailwindcss.exe`) is already included in your project.

If you need to download a fresh copy, visit the official [Tailwind CSS GitHub releases](https://github.com/tailwindlabs/tailwindcss/releases).

### Build Tailwind CSS

Run the following command in your terminal to process your **input.css** and generate the final **styles.css**:

```sh
tailwindcss.exe -i css/input.css -o css/styles.css --watch
```

This ensures Tailwind compiles and updates in real-time as you modify your files.

### Link Tailwind CSS in HTML

Ensure your HTML files link the generated **styles.css** file correctly:

```html
<link rel="stylesheet" href="css/styles.css" />
```

## 🚀 Running the Project

Simply open **index.html** in your browser or use a local server like:

```sh
npx serve .
```

Alternatively, use **Live Server** in VS Code.

## 📌 Features

- Plain HTML, CSS, and JavaScript.
- Tailwind CSS standalone CLI for styling.
- No npm or external dependencies required.
- Responsive design using Tailwind utility classes.

## 📜 License

This project is open-source. Feel free to modify and use it as needed.

---

### 📢 Notes

- Ensure you have **Git Bash** or a terminal that supports executing `.exe` files.
- Modify the **tailwind.config.js** file as per project requirements.
- To optimize for production, use `--minify`:
  ```sh
  tailwindcss.exe -i css/input.css -o css/styles.css --minify
  ```
