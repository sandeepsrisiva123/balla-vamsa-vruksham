# 🌳 బళ్ల వారి వంశ వృక్షం (Balla Family Tree)

An interactive Telugu family tree website that visually represents seven generations of the **బళ్ల (Balla)** family, beginning with **శ్రీ బళ్ల వీరభద్రుడు & శ్రీమతి అచ్చమ్మ**.

## 🔗 Live Website

**https://sandeepsrisiva123.github.io/balla-vamsa-vruksham/**

---

## 📖 Overview

This project presents the Balla family lineage in a beautiful and interactive tree structure. It includes:

* 🌳 Seven generations of family history
* 📌 Expandable and collapsible branches
* 🔍 Zoom in, zoom out, and reset controls
* 🖱️ Drag-to-pan navigation
* 📊 Automatic member and branch counting
* 📱 Responsive design for desktop and mobile
* 📝 Telugu typography using Google Fonts

---

## ✨ Features

### 🌿 Interactive Family Tree

* Parent-child relationships displayed visually.
* Each node represents an individual or couple.
* Branches can be expanded or collapsed independently.

### 🔍 Zoom Controls

* Zoom In
* Zoom Out
* Reset to 100%

### 🌲 Expand / Collapse All

* Open all branches at once.
* Collapse the tree back to the main structure.

### 🖱️ Drag Navigation

Large trees can be explored by dragging horizontally and vertically.

### 📊 Statistics

Displays:

* Total generations
* Total family members
* Total branches

### 📱 Responsive Layout

Optimized for both desktop and mobile devices.

---

## 🛠 Technologies Used

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Fonts

Google Fonts:

* Noto Serif Telugu
* Noto Sans Telugu

### Hosting

GitHub Pages

---

## 📂 Project Structure

```
balla-vamsa-vruksham/
│
├── index.html          # Main webpage
├── README.md           # Project documentation
└── assets/             # Optional images and resources
```

---

## 🌳 Data Structure

Family data is stored in JavaScript as a nested object:

```javascript
const TREE = {
  name: "శ్రీ బళ్ల వీరభద్రుడు & శ్రీమతి అచ్చమ్మ",
  gen: 1,
  children: [
    {
      name: "శ్రీ బళ్ల కనకరాజు & శ్రీమతి చిట్టిమ్మ",
      gen: 2,
      children: [
        ...
      ]
    }
  ]
};
```

Each member contains:

| Property   | Description           |
| ---------- | --------------------- |
| `name`     | Person or couple name |
| `gen`      | Generation number     |
| `children` | Descendants           |

---

## 🎨 Design Highlights

### Hero Section

Displays:

* Family title
* Generational description
* Statistics

### Tree Nodes

* Generation tags
* Child counters
* Expand/Collapse buttons

### Color Theme

Inspired by:

* Tree bark
* Leaves
* Parchment paper
* Traditional heritage colors

---

## 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/sandeepsrisiva123/balla-vamsa-vruksham.git
```

Open:

```text
index.html
```

No build process or dependencies are required.

---

## 🌐 Deployment

Hosted using **GitHub Pages**.

After pushing changes:

```bash
git add .
git commit -m "Update family tree"
git push origin main
```

GitHub Pages automatically publishes the latest version.

---

## 📜 Family Heritage

This project preserves the lineage and heritage of the **బళ్ల కుటుంబం**, beginning with:

### 🧬 1st Generation

**శ్రీ బళ్ల వీరభద్రుడు & శ్రీమతి అచ్చమ్మ**

and extending across seven generations, documenting the descendants and branches of the family.

---

## 👨‍💻 Author

**Sandeep B**

GitHub:
https://github.com/sandeepsrisiva123

---

## 📄 License

This project is intended for family heritage preservation and personal use.

---

### 🌳 "తరం తరానికి కొనసాగుతున్న వారసత్వం"
