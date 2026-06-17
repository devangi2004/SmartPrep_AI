# SmartPrep AI 🎓🤖

SmartPrep AI is an AI-powered learning platform that provides personalized study assistance, intelligent tutoring, and real-time coding practice. The platform integrates Google Gemini AI for interactive learning support and Judge0 API for code execution and evaluation.

## ✨ Features

- 🤖 AI-powered learning assistance with Google Gemini AI
- 💬 Interactive chatbot for doubt solving and concept explanations
- 💻 Real-time code execution and evaluation using Judge0 API
- 📝 Coding practice with instant feedback
- 🔐 User authentication and secure access
- 📚 Personalized learning experience
- 📱 Responsive and user-friendly interface

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### APIs & Services
- Google Gemini AI
- Judge0 API

### Deployment
- Vercel

---

## 📂 Project Structure

```text
SmartPrep_AI/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── package.json
│   └── server.js
│
├── frontend/
│   ├── assets/
│   ├── src/
│   ├── App.js
│   ├── index.js
│   ├── package.json
│   └── vercel.json
│
├── LICENSE
└── README.md
````

---

## 🚀 Installation and Setup

### Prerequisites

Ensure you have the following installed:

* Node.js (v18 or later)
* npm
* MongoDB

### 1. Clone the Repository

```bash
git clone https://github.com/devangi2004/SmartPrep_AI.git
cd SmartPrep_AI
```

### 2. Setup Backend

Navigate to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `backend` directory and add:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
JUDGE0_API_KEY=your_judge0_api_key
```

Start the backend server:

```bash
npm start
```

---

### 3. Setup Frontend

Open a new terminal and navigate to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the frontend application:

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

---

## 🔗 API Integrations

### Google Gemini AI

Used for:

* Personalized study assistance
* Intelligent tutoring
* Question answering
* Concept explanations

### Judge0 API

Used for:

* Real-time code execution
* Multi-language code evaluation
* Instant coding feedback

---

## 📸 Screenshots

Add application screenshots or demo GIFs here.

---

## 🔮 Future Enhancements

* AI-generated quizzes and assessments
* Learning progress analytics dashboard
* Gamification and leaderboards
* Multi-language support
* Adaptive learning recommendations

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch:

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Add feature"
```

4. Push to the branch:

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.
---

## 👩‍💻 Author

**Devangi Inani**

* GitHub: [@devangi2004](https://github.com/devangi2004)
* Repository: [https://github.com/devangi2004/SmartPrep_AI](https://github.com/devangi2004/SmartPrep_AI)
