Todo App
This is a simple Todo application built with React and Vite. The app allows users to add, toggle, and delete todo items. The state of the todos is persisted in the browser's local storage.

Features
Add Todo: Users can add new todo items using the input form.
Toggle Todo: Users can mark todo items as completed or incomplete by toggling the checkbox.
Delete Todo: Users can delete todo items from the list.
Local Storage: The state of the todos is saved in the browser's local storage, so the list persists even after refreshing the page.
Components
App.jsx
The main component that manages the state of the todos and renders the NewTodoForm and TodoList components.

NewTodoForm.jsx
A form component that allows users to add new todo items.

TodoList.jsx
A component that renders the list of todo items. It uses the TodoItem component to render each item.

TodoItem.jsx
A component that renders an individual todo item with a checkbox to toggle its completion state and a button to delete the item.

Styles
The app uses a simple CSS file (styles.css) to style the components. The styles include basic layout, form styling, and button styling.

Usage
To run the app locally, follow these steps:

Clone the repository.
Install the dependencies using npm install.
Start the development server using npm run dev.
