# 📝 React Assignment: Authenticated Posts App

## 🎯 Objective
Build a React application that uses the authenticated [DummyJSON Posts API](https://dummyjson.com/docs/posts) to implement a basic login and posts browsing experience.

---

## ✅ Requirements

### 🔐 1. Login Page
- Use the DummyJSON authentication API:  
  `POST https://dummyjson.com/auth/login`
- Accept **username** and **password**
- On successful login:
  - Store the returned token
  - Redirect to the posts page
- On failure:
  - Show a proper error message

> Use any of the dummy credentials listed in the API documentation.

---

### 📝 2. Posts Page
- Fetch posts using:  
  `GET https://dummyjson.com/auth/posts`
- Include the token from login in the posts api
- Display a list of posts:
  - Show **title**, **body** (truncated), **tags**, and **reactions**

---

## 🔄 Additional Requirements
- Use **React functional components**
- Use **React Router** to navigate between `/login` and `/posts`
- Implement **protected routes** (don’t allow access to `/posts` without login)
- Show **loading** and **error states**
- Clean and usable UI (does not need to be pixel-perfect)

---

---

Good luck!
