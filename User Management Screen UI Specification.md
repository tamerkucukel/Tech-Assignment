## Overview
The User Management Screen is designed for the management of user accounts within the system. It consists of three main components: a top bar with user interaction buttons and filtering option, a table displaying user information with sorting and filtering capabilities, and a form for adding or editing user details.

## Top Bar
- The top bar provides quick access to key functionalities and filtering options.
- It includes the following components:
  - **New User Button:** Clicking this button initiates the process of adding a new user.
  - **Save User Button:** This button saves any changes made to the currently selected user.
  - **Hide Disabled User Checkbox:** Toggling this checkbox filters out disabled users from the table.

## User Table
- The user table is located on the left side of the screen and displays user information in a tabular format.
- It consists of four columns: ID, User Name, Email, and Enabled Status.
- Features include:
  - **Filtering:** Users can filter the table based on any of the displayed columns.
  - **Sorting:** Users can sort the table based on any of the displayed columns by clicking on the column headers.

## User Form
- The user form is located on the right side of the screen and is used for adding or editing user details.
- It comprises six different components:
  - **Title:** Displays the selected user's name or "New User" when adding a new user.
  - **Username:** Input field for the user's username.
  - **Display Name:** Input field for the user's display name.
  - **Phone:** Input field for the user's phone number.
  - **Email:** Input field for the user's email address.
  - **User Roles:** Dropdown menu to select existing roles for the user.
  - **Enabled Status Checkbox:** Checkbox to indicate whether the user is enabled or disabled.

## Initial Display
- Upon initial loading, the user table should display a list of all users with their respective details with ascending order of ID.
- The user form should be empty, ready to add a new user.
- The "Hide Disabled User" checkbox should be unchecked by default, showing all users, including disabled ones.

## User Interaction
- **Adding a User:**
  - Click the "New User" button on the top bar.
  - The user form should clear all fields, displaying "New User" as the title.
- **Editing a User:**
  - Click on a user's row in the table.
  - The user form should populate with the selected user's details for editing.
- **Saving Changes:**
  - After editing a user's details in the form, click the "Save User" button on the top bar.
  - Changes should be saved, and the user table should update accordingly.

## Error Handling
- Display appropriate error messages if user input is invalid or if there are issues with saving changes.
- Provide clear feedback to users on the success or failure of their actions.

## Design Considerations
- Ensure consistency in design elements such as colors, fonts, and spacing.
- Use intuitive UI components and layout to enhance user experience.
- Design should be responsive to accommodate various screen sizes and devices.
