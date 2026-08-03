# 📝 MERN Todo App

A full-stack Todo application built using the MERN stack. Users can create, view, update, and delete tasks through a clean and responsive interface.

## go check out at
 https://mern-todo-app-9xc4.onrender.com
## 🚀 Features

- ➕ Add new todos
- 📋 View all todos
- ✏️ Update existing todos
- 🗑️ Delete todos
- 💾 MongoDB database integration
- ⚡ RESTful API using Express.js
- 🎨 Responsive React frontend
- 🌐 Ready for deployment on Render

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose

---

## 📂 Project Structure

```
todos/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/todos.git
cd todos
```

### Install dependencies

```bash
npm install
```

Install frontend dependencies

```bash
npm install --prefix frontend
```

---

## 🔐 Environment Variables

Create a `.env` file in the project root.

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
NODE_ENV=development
```

---

## ▶️ Running the Application

### Development

```bash
npm run dev
```

### Production

```bash
npm run build
npm start
```

---

## 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/todos` | Get all todos |
| POST | `/api/todos` | Create a todo |
| PUT | `/api/todos/:id` | Update a todo |
| DELETE | `/api/todos/:id` | Delete a todo |

---

## 🌍 Deployment

This application is configured for deployment on **Render**.

Build Command

```bash
npm run build
```

Start Command

```bash
npm start
```

---

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
screenshots/
├── home.png
├── add-task.png
└── mobile-view.png
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yash**

- GitHub: https://github.com/reacher-virus
- LinkedIn: https://linkedin.com/in/yashAgnihotri
