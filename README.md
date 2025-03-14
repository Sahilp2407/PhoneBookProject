<h1 align="center">📱 PhoneBook Web App</h1>

<p align="center">
  <strong>A Simple Yet Powerful Contact Manager</strong><br>
  🧠 Built with JavaScript, HTML5 & Bootstrap • ⚡ Fast, Interactive, and Fully Responsive • 🛠️ Client-Side Only • 🧾 Add, Edit, Delete Contacts in Real-Time
</p>

---

## 🧭 Table of Contents

- [📌 About the Project](#-about-the-project)
- [🎯 Features](#-features)
- [🛠️ Tech Stack](#-tech-stack)
- [🧩 Flow of the App](#-flow-of-the-app)
- [🚀 Getting Started](#-getting-started)
- [🔍 How to Access the Project](#-how-to-access-the-project)
- [📸 UI Preview](#-ui-preview)
- [🧠 Author Insights](#-author-insights)
- [📃 License](#-license)

---

## 📌 About the Project

The **PhoneBook Web App** is a dynamic and beginner-friendly contact manager built using vanilla JavaScript. It allows users to:

- Store contacts (Name + Phone)
- View contact list in real time
- Edit & update existing contacts
- Delete contacts on the fly

All done **without any backend**—purely client-side magic using the DOM!

---

## 🎯 Features

✅ Add contacts with name and phone number  
✅ View list of all saved contacts  
✅ Edit contact details  
✅ Delete any contact  
✅ Built-in validation for empty fields  
✅ Responsive layout using **Bootstrap 5**  
✅ Instant updates using **DOM manipulation**

---

## 🛠️ Tech Stack

| Tech         | Description                        |
|--------------|------------------------------------|
| HTML5        | Structure of the Web App           |
| CSS / Bootstrap 5 | Styling and Responsive Design    |
| JavaScript   | Logic, DOM Manipulation            |
| GitHub       | Version control and deployment     |

---

## 🧩 Flow of the App

```mermaid
flowchart TD
    A[User Opens Web App] --> B[Enters Contact Details]
    B --> C{Validation Check}
    C -->|Valid| D[Contact Added to Array]
    C -->|Invalid| E[Show Alert Message]
    D --> F[Display Contact in Table]
    F --> G[Options: Edit or Delete]
    G --> H[Update Data in Array]
    G --> I[Remove Contact from Array]
