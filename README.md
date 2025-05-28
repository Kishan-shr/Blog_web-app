#Blog Web APP 


A modern blog web app built with React, Vite, Tailwind CSS, Redux Toolkit, Appwrite, and more.

## ✨ Features

- 🔐 **Authentication** (Sign up, Login, Logout) with Appwrite
- 📝 **Create, Edit, Delete** blog posts
- 🖼️ **Image upload** & preview
- 🧑‍💻 **Rich text editor** (TinyMCE)
- 📱 **Responsive UI** powered by Tailwind CSS
- ⚡ **Fast** and **lightweight** (Vite)
- 🗂️ **State management** with Redux Toolkit
- 🔄 **Routing** with React Router

## Tech Stack

## 🛠️ Tech Stack

| 🚀 Tech                | 🌐 Description                |
|------------------------|------------------------------|
| ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) | Frontend UI library      |
| ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white) | Lightning-fast build tool |
| ![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-38B2AC?logo=tailwindcss&logoColor=white) | Utility-first CSS framework |
| ![Redux Toolkit](https://img.shields.io/badge/-Redux%20Toolkit-764ABC?logo=redux&logoColor=white) | State management         |
| ![React Redux](https://img.shields.io/badge/-React%20Redux-593D88?logo=redux&logoColor=white) | React bindings for Redux |
| ![React Router](https://img.shields.io/badge/-React%20Router-CA4245?logo=reactrouter&logoColor=white) | Routing library          |
| ![Appwrite](https://img.shields.io/badge/-Appwrite-F02E65?logo=appwrite&logoColor=white) | Backend as a Service     |
| ![React Hook Form](https://img.shields.io/badge/-React%20Hook%20Form-EC5990?logo=reacthookform&logoColor=white) | Forms & validation       |
| ![TinyMCE](https://img.shields.io/badge/-TinyMCE-292929?logo=tinymce&logoColor=white) | Rich text editor         |
| ![HTML React Parser](https://img.shields.io/badge/-html--react--parser-222222?logo=html5&logoColor=white) | HTML parsing in React    |

## Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/Kishan-shr/Blog_web-app
cd Blog_web\ app
```
### 2. Install dependencies

```
npm install
npm install @reduxjs/toolkit appwrite react-hook-form @tinymce/tinymce-react html-react-parser
```

### 3. Configure environment variables

```
cp [.env.sample](http://_vscodecontentref_/0) .env

Edit .env:
VITE_APPWRITE_URL="your-appwrite-endpoint"
VITE_APPWRITE_PROJECT_ID="your-project-id"
VITE_APPWRITE_DATABASE_ID="your-database-id"
VITE_APPWRITE_COLLECTION_ID="your-collection-id"
VITE_APPWRITE_BUCKET_ID="your-bucket-id"
```
### 4.  Scripts

```
npm run dev – Start development server
npm run build – Build for production
npm run preview – Preview production build
npm run lint – Lint code with ESLint

```
## 📁 Project Structure

```
Blog_web app/
├── public/                # Static files (favicon, etc.)
├── src/                   # Source code
│   ├── appwrite/          # Appwrite service & authentication logic
│   ├── assets/            # Images and static assets
│   ├── components/        # Reusable UI components
│   ├── conf/              # Configuration files
│   ├── pages/             # Page components (AddPost, EditPost, etc.)
│   ├── store/             # Redux slices & store setup
│   ├── App.jsx            # Main App component
│   └── main.jsx           # Entry point
├── [.env.sample](http://_vscodecontentref_/1)            # Example environment variables
├── [index.html](http://_vscodecontentref_/2)             # HTML template
├── [package.json](http://_vscodecontentref_/3)           # Project metadata & scripts
├── [postcss.config.js](http://_vscodecontentref_/4)      # PostCSS config
├── [tailwind.config.js](http://_vscodecontentref_/5)     # Tailwind CSS config
└── [README.md](http://_vscodecontentref_/6)              # Project documentation
```
### License

```
MIT
```


