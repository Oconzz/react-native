
# React Native Projects - Mobile Applications for Android and iOS

Welcome to my repository, where I showcase the projects developed during the **React Native: Desenvolva APPs Nativas para Android e iOS** course. This course covers everything needed to build cross-platform mobile applications using React Native, a framework that allows developers to create apps for both **Android** and **iOS** with a single codebase.

## Table of Contents

- [About the Course](#about-the-course)
- [Technologies Covered](#technologies-covered)
- [Projects](#projects)
  - [Project 1: Calculadora](#project-1-calculadora)
  - [Project 2: Campo Minado](#project-2-campo-minado)
  - [Project 3: ToDo List](#project-3-todo-list)
  - [Project 4: Intragram](#project-4-intragram)
- [Folder Structure](#folder-structure)
- [How to Run the Projects](#how-to-run-the-projects)

## About the Course

This course focuses on the development of **native mobile applications** for both Android and iOS using **React Native**, a powerful framework that allows developers to write the same JavaScript codebase for multiple platforms. Throughout the course, I learned about:

- React fundamentals and lifecycle.
- Component creation and management.
- Styling with **Flexbox** for mobile layouts.
- State management with **Redux**.
- Interaction with device features like the **camera** and handling **gestures**.
- Integration with a **backend** and **Firebase** for NoSQL databases and user authentication.

During the course, we developed four exciting projects inspired by real-world applications.

## Technologies Covered

- **Frontend**: React, React Native, JavaScript, Redux
- **Backend**: Node.js (for the ToDo List project), Firebase (for the Intragram project)
- **Mobile Features**: Flexbox, Navigation, Camera, Gestures, Image Gallery
- **State Management**: Redux
- **Database**: Firebase (NoSQL) for storage and authentication, and a relational database for the ToDo List project.

## Projects

### Project 1: Calculadora

- **Description**: A simple calculator to demonstrate how to organize UI elements into reusable components using Flexbox for mobile layouts.
- **Technologies**: React Native, JavaScript
- **Folder**: `calculadora/`

### Project 2: Campo Minado

- **Description**: A mobile version of the classic Minesweeper game. This project focuses on mastering **Flexbox** for mobile layouts while creating an interactive and fun game.
- **Technologies**: React Native, JavaScript, Flexbox
- **Folder**: `campo-minado/`

### Project 3: ToDo List

- **Description**: A beautiful and well-designed **ToDo List** application with more advanced UI. This project also integrates a backend **API** built with Node.js and uses a relational database to store tasks.
- **Technologies**: React Native, JavaScript, Node.js, Express, MySQL
- **Folder**: `todo-list/`

### Project 4: Intragram

- **Description**: A photo-sharing app inspired by Instagram. This project integrates the mobile device's **camera** and **gallery** and uses **Firebase** for NoSQL storage, user authentication, and image storage.
- **Technologies**: React Native, Firebase, JavaScript, Camera, Gallery
- **Folder**: `intragram/`

## Folder Structure

The repository is structured as follows:

```bash
react-native-projects/
│
├── calculadora/               # Calculator App
├── campo-minado/              # Minesweeper Game
├── todo-list/                 # ToDo List App with Node.js backend
├── intragram/                 # Photo-sharing App (like Instagram)
│
└── README.md                  # Project documentation
```

Each project folder contains its own `README.md` with detailed instructions on how to run the project.

## How to Run the Projects

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/seu-usuario/react-native-projects.git
   ```

2. **Navigate to a Specific Project Folder**:
   ```bash
   cd calculadora
   ```

3. **Install Dependencies**:
   Each project may require specific dependencies. You can install them using npm or yarn:
   ```bash
   npm install
   # or
   yarn install
   ```

4. **Run the Project**:
   Use React Native's CLI to run the project on a connected Android/iOS device or simulator:
   ```bash
   npx react-native run-android
   # or for iOS
   npx react-native run-ios
   ```

