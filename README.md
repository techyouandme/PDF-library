Here’s a professional GitHub README you can directly copy and paste for your PDF Library project:

---

# 📚 Dark PDF Library

An **interactive, responsive, and modern PDF resource library** built with **HTML, Tailwind CSS, and JavaScript**.
This library contains **hundreds of categorized PDF resources** — covering topics from **Web Development, Programming, Data Science, Databases, Career Preparation, Placement Material**, and much more.

It features a **beautiful glassmorphism UI**, category-based filtering, search functionality, and an in-browser PDF preview for a seamless learning experience.

---

## 🚀 Features

* 🎨 **Modern UI** with Glassmorphism & Dark Mode.
* 📂 **Well-organized categories & subcategories**.
* 🔍 **Instant search** to quickly find PDFs.
* 📖 **Built-in PDF viewer** with fullscreen support.
* ✅ **Mark-as-read** progress tracking.
* 📱 **Fully responsive** for all devices.

---

## 📂 Categories Overview

| Category                      | Example Subcategories                 | Example PDFs                          |
| ----------------------------- | ------------------------------------- | ------------------------------------- |
| API Development               | Guides, Courses, Cheatsheets          | API Terminology Guide, IBM API Course |
| Web Development               | HTML, CSS, JavaScript, Frameworks     | React Notes, Pro MERN Stack           |
| Programming Languages         | Python, Java, C, PHP                  | Python Cheat Sheet, Java Notes        |
| Databases                     | SQL, MongoDB                          | SQL Cheat Sheet, MongoDB Notes        |
| Data Science & AI             | Machine Learning, Deep Learning       | ML Cheat Sheet, Deep Learning Notes   |
| Career Preparation            | Resume, Interview Q\&A                | Resume Guide, 240 Java Q\&As          |
| Placement Material            | Aptitude, Coding, Technical           | Cracking the Coding Interview         |
| General Learning Resources    | Collections, Cheat Sheet Compilations | 500+ Free Resources                   |
| Software Development Concepts | Cybersecurity, Blockchain             | Cybersecurity Essentials              |
| Developer Tools               | Git, Linux, VS Code                   | Git Notes, Linux Commands             |

*(And many more…)*

---

## 🛠️ Tech Stack

* **HTML5**
* **Tailwind CSS**
* **JavaScript (Vanilla)**
* **Font Awesome** for icons

---

## 📦 Installation & Usage

1. **Clone this repository**

   ```bash
   git clone https://github.com/yaswanth-yashu/PDF-library.git
   ```

2. **Open `index.html`** in your browser.

   * No server or dependencies required — runs directly in the browser.

---

## 📸 Screenshots
<img width="1919" height="902" alt="PDF-Library" src="https://github.com/user-attachments/assets/8b631ca3-0d6f-47c7-86e4-7933cf55d6bd" />

---

## ⭐ Contribute & Support

If you find this project useful:

* **Star this repository** ⭐ to show support.
* **Fork and contribute** — Add more PDFs or improve features.

---
````markdown
## ➕ How to Add New PDFs

All PDFs are listed inside the `pdfData` array in the **`index.html`** file.

### Structure:
```json
{
  "category": "Category Name",
  "subcategory": "Subcategory Name",
  "resources": [
    {
      "name": "PDF Display Name",
      "file_link": "PDF embed link",
      "thumbnail": "Image URL for thumbnail"
    }
  ]
}
````

### Steps:

1. **Host your PDF** (Google Drive recommended)

   * Upload the PDF to Google Drive.
   * Right-click → **Get Link** → Set *"Anyone with link can view"*.
   * Replace `/view` with `/preview` in the link for embedding.

2. **Get a thumbnail image** *(Optional but recommended)*

   * Use the Google Drive image link:

     ```
     https://lh3.googleusercontent.com/d/FILE_ID=s1024?authuser=0
     ```

3. **Edit `pdfData` in `index.html`**

   * Add a new object for your PDF following the format above.
   * If the category already exists, just add your PDF inside its `resources` array.

4. **Save & refresh**

   * Your PDF will appear instantly in the library.
---
