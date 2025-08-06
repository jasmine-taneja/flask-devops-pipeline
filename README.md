# Flask DevOps Pipeline 🚀

A fully automated **CI/CD pipeline** for a Python Flask web application, built with **GitHub Actions**, **Docker**, **SonarCloud**, and deployed to **AWS EC2**.

---

## 🚀 Features

- **Flask API App** built with Python and deployed securely.
- **CI/CD using GitHub Actions** — automated workflows that handle linting, testing, image build, and deployment.
- **Dockerized deployment** — application packaged in Docker container and pushed to Docker Hub.
- **Static code analysis** with SonarCloud to maintain code quality.
- **Deployment to AWS EC2** using shell scripts over SSH for production-ready release.

---

## 🧰 Tech Stack

| Tool / Platform     | Description                                           |
|---------------------|-------------------------------------------------------|
| Python & Flask      | Backend framework and API endpoints                   |
| GitHub Actions      | CI/CD pipelines for automation                        |
| Docker              | Containerization of application                       |
| Docker Hub          | Container registry for storing Docker images          |
| SonarCloud          | Code quality, linting, and vulnerability analysis     |
| AWS EC2             | Deployment target server via SSH                      |

---

## 📁 Project Structure
.
├── app.py                     # Main Flask application
├── Dockerfile                 # Instructions to containerize the app
├── docker-compose.yml         # Defines services for local testing
├── .github/
│   └── workflows/
│       └── ci-cd.yml          # GitHub Actions CI/CD workflow
├── deploy.sh                  # Shell script to deploy to AWS EC2 via SSH
└── sonar-project.properties   # Configuration file for SonarCloud analysis

