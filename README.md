# EmployWiseA

EmployWiseA is a React-based employee management application that includes user authentication, user listing, and editing functionalities. This project is built using TypeScript and React, and it utilizes React Router for navigation.

## Live Demo
You can check out the live version of the project here:  
🔗 [EmployWise Live](https://employwisevinayakdwivedi.netlify.app/)

## Features

### 1. **Login System**
- Users can log in using:
  - **Email:** `eve.holt@reqres.in`
  - **Password:** `cityslicka`
- Error handling is implemented to manage incorrect credentials and missing fields.

### 2. **User Management**
- A list of users is displayed on the **Users** page.
- Users can be searched and filtered for easier access.

### 3. **Edit User**
- Users can edit details using the **EditUser.tsx** component.
- Error handling ensures required fields are validated before submission.

## Project Structure
The core components are located in the `src/Components` folder:
- `Login.tsx` - Handles user authentication.
- `Users.tsx` - Displays the list of users.
- `EditUser.tsx` - Allows editing of user details.

## Installation and Running the Project
Follow these steps to set up and run the project:

### 1. Clone the repository
```bash
git clone https://github.com/Vinayak-Dwivedi/EmployWiseA.git
cd EmployWiseA
```

### 2. Install dependencies
```bash
yarn install
```

### 3. Run the project
```bash
yarn run dev
```

### 4. Open in Browser
- The application will be available at `http://localhost:5173/` (or the port specified by Vite).

## Error Handling
- Displays error messages for incorrect login credentials.
- Validation checks for required fields in the user editing form.
- Handles API call failures with appropriate user notifications.

## Technologies Used
- React (TypeScript)
- React Router
- Vite (for fast development)
- Yarn (package manager)




