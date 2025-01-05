# 📝 TO-DO App

A sleek and straightforward TO-DO app that helps you manage your daily tasks effortlessly. The app features a user-friendly interface with real-time updates and an elegant design.

---

## 🌟 Features

- 🕒 **Dynamic Date and Time:** Displays real-time date and time updates.
- ➕ **Task Management:** Add tasks to a visually appealing, dynamic list.
- 🎨 **Responsive Design:** Clean layout with hover effects for an enhanced user experience.
- ✨ **Interactive UI:** Simple input field and button for task addition.

---

## 🎥 Screenshot

![TO-DO App Screenshot](https://drive.google.com/uc?id=1zKbxDyZVcwVyhglSnv5iHlGl0-JSL9ul)

---

## 📂 Project Structure

### 1. **HTML** (`index.html`)
   - Defines the structure of the app, including task input, list, and dynamic date display.
   - Includes jQuery for additional interactive features.

### 2. **CSS** (`style.css`)
   - Styles the app with a modern, responsive layout.
   - Features hover effects, rounded edges, and a clean white card design.

### 3. **JavaScript** (`app.js`)
   - Implements the core functionality to dynamically add tasks to the list.

---

## 🚀 How to Run

1. Clone or download the repository.
2. Place all files in the same directory.
3. Open the `index.html` file in your favorite web browser.

---

## 🛠️ Usage Instructions

1. Open the app in your browser.
2. Enter a task in the input field labeled **"Enter a new task."**
3. Click the **"Add Task"** button to add it to the task list.
4. Watch the real-time date and time display update automatically.
5. Hover over tasks to enjoy subtle interaction effects.

---

## 🛠️ Core Features in Code

### Dynamic Task Addition:
```javascript
btn.addEventListener("click", () => {
    const newli = document.createElement("li");
    const value = input.value;
    newli.innerText = value;
    add.appendChild(newli);
    input.value = "";
});
Real-Time Date Display:
javascript
Copy code
function updateDateTime() {
    const now = new Date();
    const formattedDate = now.toLocaleString();
    $('#currentDateTime').text(formattedDate);
}
setInterval(updateDateTime, 1000);
```
 ##   🎨 Styling Highlights
Background: A visually engaging image gives a polished look.
Centered Layout: Uses flexbox for perfect centering.
Interactive Buttons: Hover effects enhance the UI experience.
Task List Design: Clean, minimalist style with hover color changes.
## 🛠️ Future Enhancements
- 🗑️ Add delete functionality for tasks.
- ✏️ Enable task editing.
- 💾 Save tasks using localStorage or integrate a backend database.
- 📋 Organize tasks by categories or priorities.
## 📜 License
This project is licensed under the MIT License.
🤝 Credits
## Background Image: Michaela St on Unsplash
## Libraries Used: jQuery 3.6.0
Feel free to suggest improvements or contribute to this project!
