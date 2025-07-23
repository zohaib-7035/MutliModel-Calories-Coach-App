
# 🥗 Calorie Coach App

A simple Flask-based web application that helps users calculate their daily calorie needs based on their weight, height, age, and activity level.

## 🚀 Features

- Enter personal data (age, gender, weight, height, activity level)
- Calculate recommended daily calorie intake using the Mifflin-St Jeor Equation
- Clean and responsive UI using HTML and CSS (in `templates` and `static` folders)

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS (Jinja2 templating)
- **Environment**: Virtual Environment (venv)

## 📁 Project Structure

```

cal\_coach\_app/
│
├── app.py               # Main Flask application
├── templates/           # HTML templates (Jinja2)
│   └── index.html
├── static/              # CSS files
│   └── style.css
└── my\_env/              # Virtual environment (not uploaded to GitHub)

````

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/zohaib-7035/cal_coach_app.git
cd cal_coach_app
````

### 2. Create and activate a virtual environment

```bash
python3 -m venv my_env
source my_env/bin/activate  # On Windows use: my_env\Scripts\activate
```

### 3. Install dependencies

```bash
pip install Flask
```

### 4. Run the app

Make sure port 5000 is free, then:

```bash
python app.py
```

If port 5000 is in use, run on a different port:

```bash
flask run --port=5001
```

Then open your browser to:

```
http://127.0.0.1:5000
```

(or use the alternative port if changed)

## 🌐 Deployment

You can deploy this app on platforms like:

* **Render**
* **Railway**
* **Heroku**
* **PythonAnywhere**

> Make sure to configure a `requirements.txt` file and use a production-ready server like `gunicorn` for deployment.

## 📸 Screenshots

*Add screenshots of the UI here (optional)*

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments

Inspired by simple health tracking tools and Flask-based web development tutorials.

---


