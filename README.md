# 🧠 Passing Thoughts

This is a **Passing Thoughts** application that demonstrates how to manage component lifecycles, handle asynchronous operations with Promises, and perform direct DOM manipulation in React. Users can create a "thought" that appears on the screen and automatically disappears after a set amount of time.

-----

## 🚀 Features

  * **Ephemeral Thoughts**: Thoughts created by the user automatically disappear after a specific time interval.
  * **Promises**: Uses Promises to handle the asynchronous nature of the disappearing thoughts.
  * **Component-based architecture**: The app is built with a clear separation of components for better organization.
  * **DOM Manipulation**: Demonstrates how to interact with the DOM directly in a controlled manner within a React application.

-----

## 🛠️ Tech Stack

  * **Frontend**: React
  * **Asynchronous Operations**: Promises

-----

## 📂 Project Structure

```
passing-thoughts/
│
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable React components
│   │   ├── AddThoughtForm.js # Form to add a new thought
│   │   └── Thought.js      # Component for displaying a single thought
│   ├── utils/              # Helper functions
│   │   └── utilities.js    # Utility functions for the app
│   ├── App.css
│   ├── App.js              # Main application component
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .gitignore
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```

-----

## ⚙️ Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/passing-thoughts.git
    cd passing-thoughts
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Run the app:**

    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.