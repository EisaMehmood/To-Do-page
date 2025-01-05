# TO-DO App

This is a simple TO-DO app that allows users to manage their tasks effectively. The application provides an intuitive interface for adding tasks to a list and displays the current date and time dynamically.

## Features

- Add tasks to a dynamic list.
- View current date and time, updated in real-time.
- Simple, clean, and responsive user interface.
- Hover effects for improved user experience.

## Files in the Project

1. **index.html**
   - Contains the structure of the application, including input fields, buttons, and task list elements.
   - Includes jQuery for additional dynamic functionality.
2. **style.css**
   - Defines the styles for the application, including layout, typography, and hover effects.
   - Provides a visually appealing background and a responsive design.
3. **app.js**
   - Implements the core functionality of the app (e.g., adding tasks to the list).

## How to Run

1. Clone or download the repository.
2. Place all files (HTML, CSS, JS) in the same directory.
3. Open the `index.html` file in a web browser.

## How to Use

1. Open the app in your browser.
2. Enter a task in the input field labeled "Enter a new task."
3. Click the "Add Task" button to add the task to the list.
4. Hover over a task to see a background highlight effect.

## Code Highlights

- **Dynamic Date and Time**: 
  The app displays and updates the current date and time every second using JavaScript and jQuery.

- **Task Addition Logic** (in `app.js`):
  ```javascript
  btn.addEventListener("click", () => {
      const newli = document.createElement("li");
      const value = input.value;
      newli.innerText = value;
      add.appendChild(newli);
      input.value = "";
  });
Responsive Styling (in style.css): The app is styled to be responsive with flexbox layout and hover effects for a better user experience.
Preview


Dependencies
jQuery 3.6.0
Future Improvements
Add functionality to delete or edit tasks.
Implement persistent storage for tasks using localStorage or a backend database.
Add categories or priorities for tasks.
Credits
Background image by Michaela St from Unsplash.

License
This project is open-source and available under the MIT License.



Let me know if you need any adjustments or additions!
