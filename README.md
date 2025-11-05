# 🍳 Home Cooking Reviews

A simple web application that allows users to share, view, and rate home-cooked dishes. Users can log in, upload dish photos, add descriptions, and interact with other users’ posts using thumbs-up and thumbs-down icons.

---

## Description

**Home Cooking Reviews** is a Node.js and Express-based web app that integrates with MongoDB for data storage. It allows authenticated users to manage their profiles, add new dishes, and view dishes added by others.  

Each dish includes:
- A **name**
- A **description**
- An **image upload**
- Reaction buttons (👍 / 👎)

This project demonstrates basic CRUD operations, form handling with file uploads, and templating using **EJS**.

---

## Features

- **User Authentication** — Each user logs in and can only manage their own content.  
- **Add Dishes** — Upload an image, give it a name and description.  
- **View Dishes** — Displays all dishes uploaded to the database.  
- 👍👎 **Rate Dishes** — Users can upvote or downvote dishes.  
- **Delete Dishes** — Allows removal of uploaded dishes.  
- **Responsive Design** — Uses Bootstrap and Font Awesome for styling and icons.  

---

## Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML5, CSS3, Bootstrap 3, Font Awesome |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (via Mongoose) |
| **Templating Engine** | EJS |
| **Environment Variables** | dotenv |
| **File Upload Handling** | Multer or similar middleware |

---

## Installation & Setup

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`

## Credit

Modified from Scotch.io's auth tutorial
