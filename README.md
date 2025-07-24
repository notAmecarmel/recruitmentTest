
# 🌞 Back-End Assignment: Rooftop Solar Project Form

## 📌 Assignment Overview

This assignment is designed to evaluate your backend and full-stack development skills. You are required to build a simple web application that allows users to submit rooftop solar project data through a form, save it to a database, and retrieve it based on a `userId`.

---

## 🎯 Objectives

- Build a frontend form that collects project data  (done)
- Submit the form to a backend API  
- Store data in a database in the given JSON format  
- Retrieve and display projects by `userId`

---

## 🧾 Data Format

All submissions must be stored in the following JSON structure:

```json
{
  "name": "Rooftop Solar - Sample Project",
  "userId": "abc123",
  "scene": {
    "objects": [
      {
        "id": "obj1",
        "type": "panel",
        "position": [0, 0, 0],
        "rotation": [0, 90, 0]
      }
    ]
  }
}
````

---

## 🧩 Requirements

### 🔸 Frontend (done)

* A simple form to input:

  * `name` (Project Name)
  * `userId`
  * One or more objects in a scene:

    * `id`
    * `type`
    * `position` (x, y, z)
    * `rotation` (x, y, z)
* Submit button that sends the data to a backend `POST` endpoint
* Input field to enter a `userId` and button to fetch & display their projects

### 🔸 Backend

* A REST API with:

  * `POST /submit`: Accepts project data and stores it in the database
  * `GET /projects/:userId`: Returns all projects for the given `userId`

---

## 💾 Suggested Tech Stack

* **Frontend**: HTML + JS (done)
* **Backend**: Node.js + Express (or any language/framework you're comfortable with)
* **Database**: MongoDB, Firebase, or PostgreSQL

---

## ✅ What We’re Looking For

* Can you structure and validate the input data correctly?
* Can you create and connect the frontend to backend APIs?
* Can you save and retrieve data from the database?
* Can you organize your code in a clean, modular, and readable way?
* Can you use Git and GitHub correctly?

---

## 🚀 Extra Credit (Optional)

* Form validation
* UI improvements
* Hosted demo
* Bonus endpoints (e.g., delete project, edit project)
* Search/filter feature

---

## 📁 Project Structure (Recommended)

```bash
solar-form-app/
├── client/        # Frontend code (form, scripts)
├── server/        # Backend API and DB connection
├── README.md
└── .gitignore
```

---

## 🧪 Submission Instructions

1. Fork this repository or create your own public GitHub repo
2. Push your code regularly and write meaningful commit messages
3. Include clear instructions in your repo on how to run the app
4. Submit the GitHub link when done

---

## ⏱ Deadline

Will be given personally to you.

---

Good luck! 🚀

```


