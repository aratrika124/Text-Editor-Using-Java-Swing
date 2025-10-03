# 📝 TextEditor

A lightweight **Notepad-style text editor** built with **Java Swing & AWT**.  
It provides essential text editing tools along with useful extras like **Find & Replace**, **Word Wrap**, **Font customization**, and **Printing**.

---

## ✨ Features

### 📂 File Menu
- 🆕 **New File**
- 📂 **Open** (`.txt` files)
- 💾 **Save / Save As**
- 🖨️ **Print**
- 🗒️ **Page Setup**
- ❌ **Exit**

### ✏️ Edit Menu
- ✂️ **Cut**
- 📋 **Copy**
- 📌 **Paste**
- 🗑️ **Delete**
- 🔹 **Select All**
- ⏰ **Insert Date/Time**
- 🔍 **Find & Replace**
- 📍 **Go To Line**

### 🎨 Format Menu
- 🔄 **Toggle Word Wrap**
- 🔠 **Font Chooser** (family, size, style)

### ℹ️ Help
- 💡 **About Dialog**

---

## 🖥️ Requirements
- ☕ **Java 8 or higher**
- No external dependencies — everything is built using **Swing** and **AWT**.

---

## 🚀 Getting Started

### 1️⃣ Compile
```bash
javac TextEditor.java
```

### 2️⃣ Run

```bash
java TextEditor
```

➡️ The editor window will launch, allowing you to create, edit, and manage text files.

---

## 📝 Notes

* 🔄 **Word Wrap** handled with `JTextArea.setLineWrap(true)`.
* 🔠 Font selection implemented using a custom **JFontChooser** class.
* 🖨️ Printing relies on the default **Java Printing API**.
* Functions mimic a standard desktop **Notepad editor**.

---

## 📂 Project Structure

```
.
├── TextEditor.java    # Main editor GUI and logic
├── JFontChooser.java  # Custom font chooser utility
└── README.md          # Documentation
```

---

## 👤 Author

Developed by **Aratrika Samanta** ✨

### 🌐 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aratrika-samanta-67a1b5268)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aratrikasamanta060203@gmail.com)



