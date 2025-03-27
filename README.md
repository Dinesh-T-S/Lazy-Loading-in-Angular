# Lazy Loading in Angular 🚀

## 📌 Overview
This project demonstrates how to implement Lazy Loading in Angular. Instead of loading all modules at once, this approach loads modules dynamically when required, improving performance and initial load time.

## 🔹 Features
- ✅ Implements Lazy Loading for better performance
- ✅ Uses Angular Routing with loadChildren
- ✅ Separates Home and Login modules for modularity
- ✅ Reduces initial application load time

## 🎯 How It Works
- 1️⃣ Lazy Loading with Routing
- The app-routing.module.ts file is configured to dynamically load the Home and Login modules only when needed.

- 2️⃣ Feature Modules
- Both home and login modules are created as separate feature modules using RouterModule.forChild().

- 3️⃣ Navigation Between Modules
- Clicking on links will navigate to /home or /login, triggering the lazy loading mechanism.

## 🛠️ Setup Instructions
- 1️⃣ Install Dependencies
### npm install
- 2️⃣ Run the Application
### ng serve

## 🚀 Key Benefits of Lazy Loading
- ✅ Reduces initial load time by loading modules on demand
- ✅ Optimizes performance for larger applications
- ✅ Enhances maintainability by modularizing the project

🔥 Now your Angular Lazy Loading project is GitHub-ready! 🎉

## OutPut
## Home Component loaded
![home](https://github.com/user-attachments/assets/db09e312-bb5f-4e72-9e97-4987f6cdf63b)
![home component loaded](https://github.com/user-attachments/assets/1a262581-64d6-4742-9516-44c75764bdb1)
##
## The Login module is loaded only when navigating to the login page; it is not loaded before that."
![login component loaded](https://github.com/user-attachments/assets/e3a4c6cb-054e-4fb5-ac22-132a0c3d3e26)
##
## The Signup module is loaded only when navigating to the login page; it is not loaded before that."
![signup component loaded](https://github.com/user-attachments/assets/20553311-42a6-44a2-a850-ba88629a58bb)




