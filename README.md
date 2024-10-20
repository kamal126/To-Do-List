# Todo List Web Application

This is a simple and interactive **Todo List** web application built using HTML, CSS, and JavaScript. The app allows users to add, filter, and delete tasks in a user-friendly manner. It features a modern UI with basic CRUD (Create, Read, Update, Delete) functionality for managing todos.

## Features

- **Add Tasks:** Users can add new tasks using the input field.
- **Delete Tasks:** Users can delete individual tasks, selected tasks, or all tasks at once.
- **Mark as Completed:** Tasks can be marked as completed by clicking on them, and they will have a strikethrough effect.
- **Filter Options:** Users can filter the list to view:
  - All tasks
  - Pending tasks (not completed)
  - Completed tasks
- **Live Task Count:** The app shows the number of completed tasks and the total tasks.
- **Responsive Design:** The layout adjusts for smaller screens, ensuring a seamless user experience on mobile devices.

## Technologies Used

- **HTML:** To structure the content of the webpage.
- **CSS:** To style the web application and make it visually appealing, with features like hover effects and buttons.
  - Fonts are imported from Google Fonts.
  - Custom button and dropdown menu styling.
  - Media queries are used to make the app responsive.
- **JavaScript:** (Included in the `script.js` file, not shown here) for dynamically adding, filtering, and deleting todos.

## How to Use

1. **Add a Todo:**
   - Type your task in the input field and click the `+` button or press `Enter`.
   
2. **Delete Todos:**
   - Use the "Delete Selected" button to remove checked tasks or "Delete All" to remove all tasks.

3. **Filter Todos:**
   - Click on the "Filter" dropdown to view either "All," "Pending," or "Completed" tasks.

4. **View Task Count:**
   - Below the filter, you'll see the live count of completed tasks and total tasks.

## Folder Structure

```bash
|-- index.html
|-- style.css
|-- script.js
|-- to_do.png
