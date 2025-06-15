# Tesla Clone – Frontend (HTML/CSS)

This is the frontend of the Tesla Clone project. It includes a responsive homepage and a Cybertruck product page, built using HTML and CSS. It is designed to interact seamlessly with the Flask backend hosted on Render.

---

## 🌐 Live Demo

Frontend URL (Vercel): [https://tesla-clone-frontend.vercel.app](https://tesla-clone-frontend.vercel.app)  
Backend API (Flask on Render): [https://tesla-clone-backend.onrender.com](https://tesla-clone-backend.onrender.com)

---
# Tesla Clone Backend Repository (Render)

[https://github.com/NikhitaRachael/Tesla-clone](https://github.com/NikhitaRachael/Tesla-clone)

---

## 📁 Project Structure

```
Tesla-clone-Frontend/
├── index.html
├── cybertruck.html
├── 404.html
└── static/
└── css/
└── style.css
```

---

## ✨ Features

- Full-screen hero video on homepage
- Interactive, scrollable product sections (Cars & Energy)
- Product tiles with animations
- Separate Cybertruck product page
- Custom 404 error page
- Responsive design with sticky navbar

---

## 🚀 Deployment (Vercel)

1. Push the project to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) and import the repo.
3. Set the project as a **static site**.
4. Ensure the output directory is `/` (default for plain HTML/CSS).
5. Deploy!

💡 **Note**: All page routes (e.g., `/cybertruck`) must exist as real `.html` files. Vercel doesn’t support Flask-style routing.

---

## 🧪 Local Preview

You can open the site locally by just opening `index.html` in your browser, or serve it with a simple server:

```bash
# Python 3
python -m http.server
# Visit http://localhost:8000
```
---

## 🌐 Backend Integration
While this frontend is static, it is designed to mirror the routing structure of the Flask backend. Pages like /cybertruck and /404 have corresponding .html files that match Flask templates, enabling flexibility across static and dynamic environments.

## 📄 License
This project is for educational and portfolio purposes only. Not affiliated with Tesla, Inc.

## 👩‍💻 Author
Nikhita Rachael | GitHub
