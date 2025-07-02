# 📝 TextZip - Document Compression Web App

## 📖 Description

**TextZip** is a lightweight, browser-based web application that allows users to upload plain text documents and receive a compressed version for efficient storage or transmission. Built with React, this tool leverages intelligent compression algorithms to reduce file size while maintaining content integrity.

Ideal for students, professionals, or anyone working with large text files, this tool simplifies the process of minimizing document sizes without the need for third-party software.

---

## 🌟 Features

- 📤 **Upload Text Files:** Easily upload `.txt` files from your local device.
- ⚙️ **Smart Compression:** Applies lightweight text compression to reduce file size.
- 📥 **Download Output:** Download the compressed file instantly.
- 🧮 **Compression Stats:** Displays original vs compressed file size comparison.
- 💻 **Client-Side Processing:** Ensures privacy by performing all compression in-browser.

---

## 🛠️ Tech Stack

- **Frontend:** React, JavaScript, HTML5, CSS3
- **Libraries:** FileSaver.js, JSZip (or custom compression logic)
- **Hosting:** Deployable on Vercel, Netlify, or GitHub Pages

---
```text
## 📂 Project Structure

textzip-app/
│
├── public/
│ └── index.html
│
├── src/
│ ├── components/
│ │ └── FileUploader.jsx
│ │ └── Compressor.jsx
│ ├── App.js
│ ├── App.css
│ ├── index.js
│ ├── index.css
│ └── index.css
│ ├── App..test.js
│ ├── reportWebVitals.js
│ └── setupTest.js
│
├── package.json
└── README.md
```


---

## ⚙️ How to Run Locally

### 🧱 Prerequisites

Make sure you have:

- Node.js and npm installed. [Download Node.js](https://nodejs.org/)

---

Install dependencies:

```bash
npm install
```
Start the development server:

```bash
npm start
```
