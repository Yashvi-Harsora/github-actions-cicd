# 🚀 GitHub Actions CI/CD Pipeline

A simple DevOps project demonstrating Continuous Integration (CI) using **GitHub Actions** and **Docker**. The workflow automatically builds the application whenever code is pushed to the `main` branch or a pull request is created.

---

## 📌 Features

- ✅ Automated CI pipeline using GitHub Actions
- ✅ Runs on every push to the `main` branch
- ✅ Installs Node.js dependencies
- ✅ Builds Docker image automatically
- ✅ Verifies successful Docker image creation
- ✅ Easy to extend for testing and deployment

---

## 🛠️ Tech Stack

- Git
- GitHub Actions
- Docker
- Node.js
- Express.js

---

## 📂 Project Structure

```
github-actions-cicd/
│
├── app/
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   └── Dockerfile
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
└── README.md
```

---

## ⚙️ CI Workflow

The GitHub Actions workflow performs the following steps:

1. Checkout repository
2. Setup Node.js environment
3. Install project dependencies
4. Build Docker image
5. Verify Docker image creation

---

## ▶️ Run Locally

### Clone Repository

```bash
git clone https://github.com/<YOUR_USERNAME>/github-actions-cicd.git
cd github-actions-cicd
```

### Install Dependencies

```bash
cd app
npm install
```

### Run Application

```bash
npm start
```

Open your browser:

```
http://localhost:3000
```

Expected Output:

```
GitHub Actions CI/CD Project Running 🚀
```

---

## 🐳 Run with Docker

Build Image

```bash
docker build -t github-actions-demo ./app
```

Run Container

```bash
docker run -p 3000:3000 github-actions-demo
```

Visit:

```
http://localhost:3000
```

---

## 🔄 GitHub Actions Workflow

Workflow file location:

```
.github/workflows/ci.yml
```

Workflow triggers:

- Push to `main`
- Pull Request to `main`

---

## 📸 Screenshots

### GitHub Actions

_Add GitHub Actions successful workflow screenshot here._

### Docker Build

_Add Docker build screenshot here._

### Application Output

_Add browser output screenshot here._

---

## 📈 Future Improvements

- Add automated unit testing
- Docker Hub image publishing
- Continuous Deployment (CD)
- Security scanning
- Code quality checks
- Multi-stage Docker build

---

## 👩‍💻 Author

**Yashvi Harsora**

GitHub: https://github.com/<YOUR_USERNAME>

---

## ⭐ If you found this project useful, consider giving it a star.
