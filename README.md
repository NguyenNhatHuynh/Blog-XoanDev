# 🚀 Fullstack Blog Application (MERN Stack)

Welcome to the **Fullstack Blog Application**! This application allows users to explore a variety of blog posts with a user-friendly interface. Below is a detailed guide on how to set up and run the application.

## 🌟 Overview
This full-stack blog application is built using the MERN stack (MongoDB, Express, React, Node.js). The state management is handled using Zustand instead of Redux. Users can enjoy features like post categorization, pagination, commenting, and a dual Dark & Light theme UI. Admins have access to additional functionalities in the Admin Dashboard, including analytics on post content and views.

## 🛠️ System Requirements:
- 📦 **Node.js** version 18 or above.
- 🔄 **npm** version 10.2.3.
- 🗄️ **MongoDB Atlas**
- 🖋️ **Text Editor or IDE**
- 🛠️ **Git**
- 🛠️ **Postman** (Optional)

## ⚙️ Technologies Used:
- ⚛️ **ReactJs**
- 🌐 **NodeJs** (Node version 18 or above)
- 🚀 **ExpressJs**
- 🗄️ **MongoDB** (Database)
- 🎨 **Tailwind CSS** (for Styling)
- 🗂️ **Zustand** (for State Management)

## ✨ Features Include (Client side):
- 👤 **User Account Creation** (Optional)
- 🔑 **Google Sign In** (Optional) - Client side only
- 🗂️ **Post Categories**
- 🔢 **Pagination** with Page Numbers
- 💬 **Commenting on Posts** (Only Available to Signed-in Users)
- 🌗 **Dark and Light Theme** Settings
- 🔗 **Blog Details Page** with Dynamic URL (Slug)
- 📱 **Fully Mobile-Responsive Design**

## 🖥️ Features Include (Admin Dashboard):
- 👤 **Account Creation**
- 📧 **Email Verification with OTP**
- ✏️ **Create Posts, Delete Posts, Enable or Disable Posts**
- 📊 **Dashboard Analytics**
- 📈 **Content and Views Analytics** (7 days, 28 days, 900 days & 365 days)
- 🗑️ **Ability to delete user comments on a blog post**
- 🌗 **Dark and Light Theme** Settings
- 📱 **Fully Mobile-Responsive Design**
- 🖥️ **Modern User Interface (UI)** with DARK & LIGHT theme settings

## 📸 Screenshots:
_Add screenshots here to showcase the UI and features._

---

## ⚙️ **Server Setup**

### 📝 Environment variables
First, create the environment variables file `.env` in the server folder. The `.env` file contains the following environment variables:


### 🗄️ **Set Up MongoDB**:
1. Visit the [MongoDB Atlas Website](https://www.mongodb.com/cloud/atlas).
2. **Create an Account** and log in to MongoDB Atlas.
3. **Create a New Cluster**, configure the settings, and wait for deployment.
4. **Create Database User** and set up the IP Whitelist.
5. **Connect to Cluster** and configure your application.

### 🖥️ Steps to Run Server:
1. Open the project in your preferred editor.
2. Navigate to the server directory: `cd server`.
3. Install packages: `npm i`.
4. Start the server: `npm start`.
5. If configured correctly, the server should display a message that it is running and connected to the database.

---

## 🌐 **Client Side Setup**

### 📝 Environment variables
Create the `.env` file in the client folder with the following:



### 🖥️ Steps to Run Client:
1. Navigate to the client directory: `cd client`.
2. Install packages: `npm i`.
3. Start the app: `npm start`.
4. Visit `http://localhost:3000` to view the app in your browser.

---

## 🛠️ **Admin Dashboard Setup**

### 📝 Environment variables
Create the `.env` file in the admin folder with the following:



### 🖥️ Steps to Run Admin Dashboard:
1. Navigate to the admin directory: `cd admin`.
2. Install packages: `npm i`.
3. Start the app: `npm start`.

---

## 🔒 **Security Note**:
- Ensure that your environment variables are safeguarded and not exposed unintentionally.
- Only authorized personnel should have access to the environment variable configurations.

---

## 📧 **For Support, Contact**:
- Email: [xoandev@gmail.com](mailto:xoandev@gmail.com)

