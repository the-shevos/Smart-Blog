# Smart-Blog

Smart-Blog is a modern full-stack blogging platform featuring a **Node.js backend** and a **React frontend**. It is designed for efficiently creating, managing, and securely viewing blog posts online, with a clean and responsive user interface, role-based access control, and a scalable project architecture.

---

## Features

- Create, edit, and delete blog posts
- Responsive and interactive frontend UI
- User authentication and role-based access (if implemented)
- RESTful API backend for handling CRUD operations
- Organized project structure for easy maintenance

---

## Technologies

**Backend:**

- Node.js
- Express.js
- MongoDB (Mongoose)
- bcrypt (password hashing)
- JWT (authentication)

**Frontend:**

- React.js
- React Router
- Tailwind CSS / CSS Modules (or your styling library)
- Framer Motion (for animations, if used)

---

## Screenshots

### Login Page

![Login Page](smart-blog-fe/public/screenshots/LoginPage.PNG)

### Home Page

![Home Page](smart-blog-fe/public/screenshots/HomePage.PNG)

### Post Page

![Post Page](smart-blog-fe/public/screenshots/PostsPage.PNG)

---

## Project Structure

```text
Smart-Blog/
├─ smart-blog-be/
│  ├─ controllers/
│  │  └─ *.controller.ts
│  ├─ models/
│  │  └─ *.model.ts
│  ├─ routes/
│  │  └─ *.routes.ts
│  ├─ middlewares/
│  │  └─ *.middleware.ts
│  ├─ utils/
│  │  └─ *.ts
│  └─ server.ts
│
├─ smart-blog-fe/
│  ├─ public/
│  ├─ src/
│  │  ├─ components/
│  │  │  └─ *.tsx
│  │  ├─ contexts/
│  │  │  └─ *.tsx
│  │  ├─ pages/
│  │  │  └─ *.tsx
│  │  ├─ services/
│  │  │  └─ *.ts
│  │  ├─ hooks/
│  │  │  └─ *.ts
│  │  ├─ styles/
│  │  │  └─ *.css
│  │  └─ main.tsx
│  └─ package.json
│
├─ .gitignore
├─ package.json
├─ tsconfig.json
└─ README.md
```
