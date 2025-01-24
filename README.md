
# Portfolio C1
Hello, everyone!
Allow me to introduce myself. I’m Eki Zulfar Rachman, and today, I’d like to share a portfolio website project that I’ve developed.

Tech Stack Used:
- ReactJS
- Tailwind CSS
- AOS
- Firebase
- Framer Motion
- Lucide
- Material UI
- SweetAlert2

Link to Website:
https://www.eki.my.id/

We would appreciate it if you would like to use this project. Please include our credit in your use. Thank you! 🙏

# Tutorial to Run the Project

Below is a simple guide to running this project.

## Preparation

Ensure you have installed:

- **Node.js**

## Steps to Run the Project

1. **Download this project:**

   ```bash
   git clone https://github.com/ChienDainn/Portfolio_C1
   ```

2. **Install all dependencies:**

   ```bash
   npm install
   ```
   Alternatively:

   ```bash
   npm install --legacy-peer-deps
   ```

3. **Run the project:**

   ```bash
   npm run dev
   ```

4. **Open in your browser:**

   Access the application in your browser using the link that appears in the terminal.

## Creating a Production Build

To create a production-ready version:

1. Run the build command:

   ```bash
   npm run build
   ```

2. The build files will be saved in the `dist` folder. You can upload this folder to your hosting server.

## Notes

If you encounter any issues while running the project, make sure:

- Node.js is installed correctly.
- You are in the correct project folder.
- All dependencies are installed without errors.

## Firebase Configuration

To configure Firebase in this project, follow these steps:

1. **Add Firebase to the Project:**
   - Open [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or use an existing project.

2. **Select Firestore Database**
   - Create Database

3. **Go to Project Settings**
   - Click on the section: ![Screenshot 2024-12-30 214204](https://github.com/user-attachments/assets/43243cad-b414-4dd9-8793-d15c401c82fe)
   - Then copy the Firebase configuration content: ![image](https://github.com/user-attachments/assets/6d0e158c-1ae0-40c1-8b41-9e53a1c4ccbb)

4. **Go to Rules**
   - Set the rules to `true`.

5. Adjust the Collection Structure as shown in the following images:
   ![Screenshot 2025-01-03 001341](https://github.com/user-attachments/assets/38580122-08a4-4499-a8fd-0f253652a239)
   ![Screenshot 2025-01-03 001410](https://github.com/user-attachments/assets/d563d7ad-f1ab-46ff-8185-640dcebd0363)

6. **Open `firebase.js` and `firebase-comment.js` files:**
   - Replace the `firebaseConfig` content with your Firebase configuration.
