# QuickNotes

QuickNotes is a lightweight, front-end web application designed for capturing thoughts, tasks, and ideas instantly. Built with vanilla HTML, CSS, and JavaScript, it provides a clean, distraction-free environment with category tagging and local data persistence.

## Features
- **Add Notes:** Quickly create notes with a text input and category dropdown (Personal, Work, Study).
- **Categorization:** Notes are visually distinct with color-coded left borders based on their category.
- **Delete Functionality:** Easily remove notes you no longer need.
- **Search:** Real-time, case-insensitive search to filter through your notes.
- **Validation:** Prevents empty notes and enforces a 200-character limit.
- **Persistence:** Automatically saves notes to the browser's `localStorage`, so data survives page refreshes.
- **Clear All:** Bonus feature to delete all notes with a confirmation prompt.

## How to Run Locally
1. Clone this repository to your local machine.
2. Navigate to the project folder.
3. Open `index.html` in any modern web browser (or use the Live Server extension in VS Code).
4. Start typing notes!

## What I Learned
1. **DOM Manipulation:** Learned how to safely create and append elements using `createElement` and `textContent` instead of `innerHTML` to prevent XSS vulnerabilities.
2. **Local Storage:** Gained practical experience with `JSON.stringify` and `JSON.parse` to persist application state across browser sessions.
3. **CSS Layouts:** Improved my understanding of Flexbox for form layouts and responsive design using media queries for mobile compatibility.
