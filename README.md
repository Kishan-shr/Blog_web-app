#Blog Web APP 


A modern blog web app built with React, Vite, Tailwind CSS, Redux Toolkit, Appwrite, and more.

## Features

- User authentication (signup, login, logout) via Appwrite
- Create, edit, and delete blog posts
- Rich text editor for post content
- Image upload and preview
- Responsive UI with Tailwind CSS
- State management with Redux Toolkit
- Routing with React Router

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Appwrite](https://appwrite.io/)
- [React Hook Form](https://react-hook-form.com/)
- [TinyMCE](https://www.tiny.cloud/) (via `@tinymce/tinymce-react`)
- [html-react-parser](https://github.com/remarkablemark/html-react-parser)

## Getting Started

### 1. Clone the repository

```sh
git clone <https://github.com/Kishan-shr/Blog_web-app>
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
### 4. Start the development server

```
npm run dev

```
## 📁 Project Structure
```
```markdown
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
├── .env.sample            # Example environment variables
├── index.html             # HTML template
├── package.json           # Project metadata & scripts
├── postcss.config.js      # PostCSS config
├── tailwind.config.js     # Tailwind CSS config
└── README.md              # Project documentation
```
```
```


