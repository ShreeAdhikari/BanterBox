# 🎭 BanterBox

> An AI-powered multilingual banter engine that understands English, Nepali, and Roman Nepali.

BanterBox is a REST API built with Node.js and Express.js that generates witty, context-aware responses using AI. It automatically understands the user's language and replies in the same language.

---

## ✨ Features

- 🤖 AI-powered responses
- 🇺🇸 English support
- 🇳🇵 Nepali support
- 🔤 Roman Nepali support
- 😂 Roast mode
- ❤️ Compliment mode
- 😎 Comeback mode
- 🎭 Meme caption mode
- 📝 Response history
- 🚀 RESTful API

---

## 🛠 Tech Stack

- Node.js
- Express.js
- Google Gemini API *(planned)*
- PostgreSQL *(planned)*
- Git & GitHub

---

## 📂 Project Structure

```
BanterBox
│
├── docs/
│
├── src/
│   ├── controllers/
│   ├── data/
│   ├── middleware/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   └── app.js
│
├── .env.example
├── .gitignore
├── package.json
├── README.md
└── server.js
```

---

## 🗺 Roadmap

### Version 0.1.0
- [x] Project setup
- [x] Git repository
- [x] Folder structure

### Version 0.2.0
- [ ] Express server
- [ ] First API endpoint

### Version 0.3.0
- [ ] AI integration

### Version 0.4.0
- [ ] Language detection

### Version 0.5.0
- [ ] Banter modes

### Version 1.0.0
- [ ] Stable release

---

## 📡 Planned API

### Generate Banter

```
POST /api/v1/banter
```

Example Request

```json
{
    "mode": "roast",
    "text": "k gardai xas"
}
```

Example Response

```json
{
    "language": "Roman Nepali",
    "response": "Ma ta timro reply parkhera basirako thiye 😏"
}
```

---

## 🎯 Goals

This project is being built to:

- Learn backend development properly
- Understand Express.js architecture
- Build production-style REST APIs
- Integrate AI into web applications
- Practice Git and GitHub workflows
- Maintain clean documentation

---

## 📄 License

MIT License