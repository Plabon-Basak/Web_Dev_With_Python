# Web Development With Python

A starter project for web development with Python using the **Flask** micro-framework, created as part of a daily learning challenge. It demonstrates the basics of routing, dynamic URL parameters, and HTML rendering with Jinja2 templates.

## Routes

| Route | Description |
|-------|-------------|
| `/` | Home page (`index.html`) — welcome to the first Flask app |
| `/greet/<name>` | Greeting page (`greet.html`) — greets the name from the URL, e.g. `/greet/John` |

## Project Structure

```
Web_Dev_With_Python/
├── app.py        # Flask application with routes
├── index.html    # Home page template
└── greet.html    # Greeting page template
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Plabon-Basak/Web_Dev_With_Python.git
cd Web_Dev_With_Python
```

### 2. Install Flask

```bash
pip install flask
```

### 3. Run the app

```bash
python app.py
```

Then open http://127.0.0.1:5000 in your browser. Visit `/greet/John` to try the dynamic greeting route.

## Note on Templates

Flask's `render_template()` expects templates inside a `templates/` folder. For the app to run out of the box, place `index.html` and `greet.html` inside a `templates/` directory (or adjust the code accordingly).

## Components

1. Python
2. Flask framework