# 📄 Sortify

**Sortify** is an intelligent, modular document management system that integrates a web backend and mobile frontend. Designed for seamless document upload, categorization, search, and retrieval, Sortify helps users stay organized across platforms.

This meta-repo brings together:

- 🔧 [`modular-sortify`](https://github.com/P-Asare/modular-sortify): A Flask-based backend with support for PDF/image processing, semantic search, translation, and cloud storage.
- 📱 [`mobile-sortify`](https://github.com/P-Asare/sortify_mobile): A Flutter mobile app that enables users to scan, upload, and intelligently organize documents on the go.

---

## 🌐 Architecture Overview

```
Sortify/
├── modular-sortify/
├── mobile-sortify/
├── .gitmodules
└── README.md
```
Both components are included as Git submodules, enabling independent development while maintaining clear integration.

---

## 🚀 Key Highlights

- 🔁 Modular monolith architecture for maintainability and scalability  
- 🧠 Semantic search with embeddings and lightweight LLMs  
- 📤 Cloud-based document and thumbnail storage  
- 🌍 Language translation with Google Translate API  
- 📱 Cross-platform mobile support with intelligent categorization  
- 🔗 RESTful API powering interaction between mobile and backend  

---

## 🛠️ Getting Started

1. **Clone the Parent Repo:**

```bash
git clone --recurse-submodules https://github.com/P-Asare/sortify.git
cd sortify
```

2. **Initialise/Update Submodules:**

```bash
git submodule update --init --recursive
```

3. **Setup each component:**

- See [modular-sortify]() for backend setup using Docker and .env configuration
- See [sortify-mobile]() for Flutter mobile setup instructions

---

## 👤 Author

**Palal Asare**  
Computer Science student | Ashesi University  
📧 palalasare.fr@gmail.com 
🌍 [LinkedIn](https://www.linkedin.com/in/palal-asare/) | [GitHub](https://github.com/P-Asare)
