# Redux Counter App

A simple React application that demonstrates state management using Redux Toolkit. The app includes a counter with various operations and an authentication system that conditionally renders components.

## Features

- **Counter Functionality**: Increment, decrement, increase by a custom value, and toggle counter visibility.
- **Authentication**: Login and logout functionality that affects which components are displayed.
- **Conditional Rendering**: Shows different components based on authentication state (Auth form, User Profile, etc.).
- **Redux State Management**: Uses Redux Toolkit for managing global state.

## Technologies Used

- React 19
- Redux Toolkit
- React Redux
- React Scripts (Create React App)

## Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd redux-counter
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

The app will open in your browser at `http://localhost:3000`.

## Usage

- **Counter**: Use the buttons to modify the counter value and toggle its visibility.
- **Authentication**: Click "Login" to authenticate and see the User Profile component. Click "Logout" to return to the Auth form.
- The Header component is always visible.

## Project Structure

```
src/
├── components/
│   ├── Auth.js
│   ├── Counter.js
│   ├── Header.js
│   └── UserProfile.js
├── store/
│   ├── index.js
│   ├── counter.js (if separated)
│   └── auth.js (if separated)
├── App.js
├── index.js
└── index.css
```

## Scripts

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner.
- `npm run build`: Builds the app for production.
- `npm run eject`: Ejects from Create React App (irreversible).

## Contributing

Feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.
