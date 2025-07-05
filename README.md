# Flask + Bootstrap Starter Project

This is a beginner-friendly starter template for building web applications using [Flask](https://flask.palletsprojects.com/) (a Python web framework) and [Bootstrap 5](https://getbootstrap.com/) (a popular CSS and JS library for responsive design).

## Features
- Flask app structure with templates and static folders
- Bootstrap 5 included via CDN for easy styling and components
- Example base template and homepage

## Getting Started

### 1. Clone the repository
```
git clone https://github.com/KdntNinja/FlaskTemplate
cd FlaskTemplate
```

### 2. Set up a virtual environment (recommended)
```
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Requirements
```
pip install -r requirements.txt
```

### 4. Run the app
```
python app.py
```
Visit [http://localhost:5000](http://localhost:5000) in your browser.

## Project Structure
```
FlaskTemplate/
├── app.py
├── static/
├── templates/
│   ├── base.html
│   └── index.html
```
- `app.py`: Main Flask application
- `templates/`: HTML templates (Jinja2)
- `static/`: Place for static files (CSS, JS, images)

## Customization
- Edit `templates/base.html` to change the layout or add more Bootstrap components.
- Add your own routes and templates in `app.py` and the `templates/` folder.
- Place custom CSS/JS in the `static/` folder and link them in your templates.

## Learn More
- [Flask Documentation](https://flask.palletsprojects.com/)
- [Bootstrap Documentation](https://getbootstrap.com/)

---
Happy coding!
p 