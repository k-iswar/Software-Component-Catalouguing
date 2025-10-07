# 📦 Software Component Cataloguing System

This project is a modern, web-based platform designed to catalogue and manage reusable software components. Built with a React frontend and Firebase backend, it provides a streamlined solution for developers and teams to discover, share, and organize code assets efficiently.

---

### Key Features

* **Component Management**: Easily add, edit, and view software components with details like name, description, category, and source code.
* **User Authentication**: Secure user login and registration system powered by Firebase Authentication to protect user data.
* **Intuitive Interface**: A clean and responsive user interface built with React and styled with Tailwind CSS for a seamless user experience.
* **Organized Categories**: Group components by category for easy browsing and discovery.
* **Real-time Database**: Leverages Firebase Firestore to ensure all data is synchronized in real-time.

---

### Technology Stack

* **Frontend**: React, TypeScript, Tailwind CSS
* **Backend & Database**: Firebase (Authentication, Firestore)
* **Build Tool**: Vite
* **Deployment**: Vercel

---

### Getting Started

To get a local copy up and running, follow these simple steps.

**Prerequisites**
* Node.js (v14 or later)
* npm or yarn

**Installation**

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/k-iswar/Software-Component-Catalouguing.git](https://github.com/k-iswar/Software-Component-Catalouguing.git)
    ```

2.  **Navigate to the project directory**:
    ```bash
    cd Software-Component-Catalouguing
    ```

3.  **Install NPM packages**:
    ```bash
    npm install
    ```

4.  **Set up Firebase**:
    * Create a project on the [Firebase Console](https://console.firebase.google.com/).
    * Create a `.env.local` file in the root of the project.
    * Add your Firebase project configuration to the `.env.local` file:
        ```env
        VITE_FIREBASE_API_KEY=your_api_key
        VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
        VITE_FIREBASE_PROJECT_ID=your_project_id
        VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
        VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
        VITE_FIREBASE_APP_ID=your_app_id
        ```

5.  **Run the development server**:
    ```bash
    npm run dev
    ```
    Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

---

### Project Structure

The project follows a standard React application structure, organizing components, pages, and services for clarity and maintainability.
