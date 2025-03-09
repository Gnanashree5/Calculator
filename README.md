# Flask Calculator App

This is a simple web-based calculator built using Flask.

## Features
- Perform basic arithmetic operations (Addition, Subtraction, Multiplication, Division).
- Interactive user interface with an HTML form.
- Built using Python and Flask.

## Project Structure
```
/flask_calculator/
│── app.py
│── /templates/
│   ├── calculator.html
│── README.md
```

## Installation
1. Clone the repository or create the necessary files.
```bash
git clone <repository_url>
cd mycalculator
```

2. Install Flask (if not installed already):
```bash
pip install flask
```

## How to Run
1. Ensure you are inside the project directory.
2. Run the Flask app:
```bash
python app.py
```
3. Open a web browser and go to `http://127.0.0.1:5000/`

## Folder & File Setup Commands (if required)
Run these commands in your terminal to create the required folders and files:
```bash
mkdir templates
cd templates
echo. > calculator.html
cd ..
echo. > app.py
```

## Troubleshooting
- **TemplateNotFound Error:** Ensure `calculator.html` is inside the `templates` folder.
- **Port Issues:** If port 5000 is busy, try running with:
  ```bash
  python app.py --port=5001

  ```
## Acknowledgment
<p>This project was done under guidance of  <a href="https://github.com/Victor-Ikechukwu">Dr. Agughasi Victor Ikechukwu</a></p>

