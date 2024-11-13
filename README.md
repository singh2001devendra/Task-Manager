# Task Management Application

## Overview
This application is a straightforward task management tool designed for efficient task tracking. It provides users with a basic dashboard that displays tasks in various categories, allows for task creation and management, and supports searching and filtering to streamline task navigation. The focus is on delivering a simple, user-friendly experience with essential task management functionalities.

## Core Features
### Dashboard
- A central dashboard displays a list of tasks upon accessing the application.
- The dashboard includes sections for:
  - **Upcoming Tasks**: Tasks that are due soon.
  - **Overdue Tasks**: Tasks that are past their due date.
  - **Completed Tasks**: Tasks marked as completed.

### Task Management
- Users can **add**, **edit**, and **delete** tasks.
- Each task includes:
  - **Title**: A short title describing the task.
  - **Description**: Additional details about the task.
  - **Due Date**: When the task should be completed.
  - **Priority Level**: A priority setting to help users focus on important tasks.

### Priority Levels
- Tasks have three priority levels:
  - **High**
  - **Medium**
  - **Low**
- Users can set and update the priority level for each task.

### Search and Filter
- A search bar allows users to quickly find tasks by keyword.
- Filters enable users to view tasks based on:
  - **Priority Level**: Filter by High, Medium, or Low.
  - **Completion Status**: View completed or incomplete tasks.

## Assumptions Made During Development
- **Task Completion**: Users manually mark tasks as completed. Once completed, tasks will appear in the "Completed Tasks" section of the dashboard.
- **Task Sorting**: Tasks are displayed in order of priority on the dashboard, with the default sort order prioritizing High, Medium, and Low priority tasks.
- **Overdue Status**: A task is considered "overdue" if the current date is past the task’s due date, regardless of priority level.
- **User Authentication**: For simplicity, user authentication is not implemented in this version.
- **UI Design**: The emphasis is on a functional, clean interface with straightforward task management options.



## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- React.js and npm (Node Package Manager) should be installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-task-management.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-task-management
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and go to [http://localhost:3000](http://localhost:3000) to access the app.

## Usage

1. **Add Task:** Click on the "Add Task" button in the respective priority section, fill in the task details, and press "Save."

2. **Edit Task:** Click on the task you want to edit, make the necessary changes, and press "Save Changes."

3. **Delete Task:** Click on the "Delete" button next to the task you want to remove.

4. **Change Priority:** Drag and drop tasks between the different priority lists to change their priority.

## Built With

- [React](https://reactjs.org/) - JavaScript library for building user interfaces.
- [Tailwind CSS](https://tailwindcss.com/) - Library for adding beautiful Styling With Responsive Design.



