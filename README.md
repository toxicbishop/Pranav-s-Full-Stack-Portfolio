# 🌐 Pranav's Full-Stack Portfolio

Welcome to my personal portfolio website! This project is a full-stack web application that showcases my skills, projects, and experience. It features a responsive frontend, a custom dark mode, and a functional backend system connected to a local MongoDB database.

## 🚀 Features

* **Responsive Design:** Works seamlessly on desktops, tablets, and mobile devices.
* **Dark Mode:** Built-in theme toggler with local storage persistence (remembers your preference).
* **Contact Form:** Functional form that sends data to a Python backend.
* **Database Integration:** Stores contact messages securely in a local MongoDB database.
* **Admin Dashboard:** A hidden `/admin.html` page to view received messages in real-time.
* **Interactive UI:** Scroll-to-top buttons, hover effects, and smooth transitions.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Backend:** Python 3, Flask
* **Database:** MongoDB (Local Community Server)
* **Tools:** VS Code, Git, GitHub
* ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)


## ⚙️ Setup & Installation

Follow these steps to run the project locally on your machine.

### 1. Prerequisites
Ensure you have the following installed:
* [Python 3.x](https://www.python.org/downloads/)
* [MongoDB Community Server](https://www.mongodb.com/try/download/community)
* pip install -r requirements.txt

### 2. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
```
### 3. Set Up the Backend
install the required Python libraries
```bash
pip install flask flask-cors pymongo
```
### 4. Run the Application
Step 1: Start MongoDB Make sure MongoDB is running in the background (it usually starts automatically after installation).
Step 2: Start the Python Server Open your terminal and run:
```bash
python app.py
```
### 5. Project Strcture
```bash
├── index.html          # Home Page
├── about.html          # About Me Page
├── contact.html        # Contact Form (Frontend)
├── products.html       # Project Showcase
├── admin.html          # Dashboard to view database messages
├── app.py              # Python Flask Backend
├── style.css           # Global Styles & Dark Mode
├── script.js           # Frontend Logic (Toggle, API calls)
├── seo.png             # Website Favicon
└── README.md           # Documentation
```
### 🤝 Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
