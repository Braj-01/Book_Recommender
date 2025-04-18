# 📚 Book Recommendation System

> A Machine Learning project built using **Collaborative Filtering** to recommend books based on user preferences. Deployed live on **Render** for easy access and demo!

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-web--framework-yellow)](https://flask.palletsprojects.com/)
[![Status](https://img.shields.io/badge/Live-Demo-brightgreen)](https://book-recommender-system-j9yw.onrender.com)

---

## 🔗 Live Demo

👉 https://book-recommender-system-j9yw.onrender.com  


---

## 💡 Project Overview

This project is a **Book Recommendation System** built using the **Collaborative Filtering** technique, which recommends books to users based on the preferences of similar users. The system learns patterns from a large dataset of user-book interactions and uses those to suggest books a user might enjoy.

Rather than relying on predefined genres or tags, this method finds *hidden relationships* between users and books. If User A and User B have similar reading habits, books liked by User B that User A hasn't read yet will be recommended to User A. This creates a personalized and smart recommendation experience.

The entire system is wrapped in a user-friendly web interface using Flask and deployed on Render for public access.

---

## 🧠 How Collaborative Filtering Works

We break down Collaborative Filtering in three simple steps:

1. **User-Item Matrix Creation** – Build a matrix where rows are users and columns are books, filled with ratings or interactions.
2. **Find Similarities** – Use techniques like cosine similarity to find users or items with similar patterns.
3. **Generate Recommendations** – Suggest books based on similar users' preferences.

---

## 📸 Screenshots

### 🔍 Home Page
![Home Page](https://github.com/Braj-01/Book_Recommender/blob/master/Screenshot%202025-04-18%20213746.png)



---

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **pandas / numpy / scikit-learn**
- **Jinja2**
- **Render** (for deployment)

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/your-username/book-recommender-system.git
cd book-recommender-system
pip install -r requirements.txt
python app.py
```

## 👨‍💻 Author & 🙌 Support

Made with ❤️ by **[Braj Narayan Awasthi](https://www.linkedin.com/in/braj-narayan-awasthi-33193a274)**

If you found this project helpful or interesting:

🌟 **Star** this repo to support the project  
🐛 **Open issues** if you find bugs or have feature requests  
🔁 **Fork** and build your own version!
