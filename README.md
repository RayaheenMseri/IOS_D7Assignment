# To-Do List SwiftUI App

This is a simple To-Do List app built using SwiftUI. The app allows users to add tasks, mark them as completed, and manage them in a user-friendly interface. It supports both light and dark modes, and provides a checkbox for each task to indicate whether it is completed.

## Features

- **Add New Tasks**: Users can add new tasks using a text field and a button.
- **Mark Tasks as Completed**: Each task includes a checkbox that allows users to mark it as completed.
- **Sort Tasks**: Incomplete tasks are displayed at the top of the list, while completed tasks are placed at the bottom.
- **Dark Mode**: The app supports dark mode automatically based on the user's system preference.
- **Customizable UI**: The UI is designed with a focus on clean visuals and ease of use, with customizable colors and fonts based on iOS design guidelines.
- **Simple and Efficient**: A straightforward design for managing tasks quickly without unnecessary complexity.

## App Design & UI

This app follows **iOS Human Interface Guidelines** to deliver a seamless user experience. Here’s a breakdown of the design choices:
  
- **Color Scheme**: The app adapts to dark and light modes, automatically switching based on the system preference. It also uses custom colors, such as Orange/Brown for buttons, to provide a pleasant and engaging look.
- **Typography**: The font weight is set to bold for action buttons and tasks, providing visual hierarchy and clarity. The task completion status is visually represented through strikethrough text for completed tasks.
- **Spacing and Layout**: Thoughtful padding and spacing are used around UI elements to ensure readability and make the user experience smooth.

## How It Works

- **Task Management**: The app allows users to add new tasks via a text field. Tasks can be marked as completed using a custom checkbox that toggles the task’s state.
  
- **Task Sorting**: The tasks are automatically sorted, ensuring that incomplete tasks are always shown at the top of the list, while completed tasks are moved to the bottom.

- **Data Persistence**: (If desired, you can extend the functionality in the future to support data persistence through CoreData or UserDefaults for saving tasks between app sessions.)

- **Custom Components**: The app uses reusable components like the custom checkbox and task list cell, ensuring clean and maintainable code.
  
