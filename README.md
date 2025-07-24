# 🌞 Full Stack Assignment: Rooftop Solar Project Form

## 📌 Assignment Overview

This assignment is designed to evaluate your backend and full-stack development skills. You are required to build a simple web application that allows users to submit rooftop solar project data through a form, save it to a database, and retrieve it based on a `userId`.

---

## 🎯 Objectives

- Build a frontend form that collects project data
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
