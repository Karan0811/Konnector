
# Konnector 🚀

## ✨ Features

- 🔐 JWT Authentication (bcrypt secured)
- 👤 User Profiles with Gravatar
- 📝 Create, Like & Comment on Posts
- 🔍 Browse & Discover Users
- ⚡ REST APIs
- 📱 Responsive UI

---

## 🛠 Tech Stack

**Backend:** Node.js, Express, MongoDB, Mongoose, JWT  
**Frontend:** React, Redux, React Router, Axios  

---

## 📁 Project Structure

```

Konnector/
├── models/
├── routes/api/
├── middleware/
├── frontend/
├── server.js

````

---

## ⚙️ Setup

```bash
# Clone repo
git clone https://github.com/Karan0811/Konnector.git
cd Konnector

# Install dependencies
npm install
npm install --prefix frontend

# Add config (config/default.json)
{
  "mongoURI": "mongodb://localhost:27017/konnector",
  "jwtSecret": "your-secret-key"
}

# Run app
npm run dev
````

* Frontend → [http://localhost:3000](http://localhost:3000)
* Backend → [http://localhost:5000](http://localhost:5000)

---

## 🔌 API (Sample)

**Auth**

* POST `/api/auth`
* GET `/api/auth`

**Users**

* POST `/api/users`

**Posts**

* GET `/api/posts`
* POST `/api/posts`
* PUT `/api/posts/like/:id`
* POST `/api/posts/comment/:id`

---

## 🚀 Deployment

* Use **MongoDB Atlas** for DB
* Deploy on **Heroku / Render / AWS**
* Set env variables: `mongoURI`, `jwtSecret`

---
