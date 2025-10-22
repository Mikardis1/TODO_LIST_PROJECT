# My To-Do List

A simple and clean **Flask web application** that lets you add, complete, and delete tasks.  

---

## Features

- Add new tasks  
- Mark tasks as completed (toggle on/off)  
- Delete tasks  
- Persistent storage with **SQLite + SQLAlchemy**




## Project Structure

```
TODO_LIST_PROJECT/
│
├── instance/
│   └── tasks.db              # SQLite database (auto-generated, ignored by Git)
│
├── templates/
│   └── index.html            # Frontend layout with Jinja2
│
├── .gitignore                # Git ignore rules (venv, __pycache__, DB, etc.)
├── main.py                   # Main Flask application
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation


```


## Installation

1. Make sure you have Python 3 installed.
2. Clone this repository:
git clone https://github.com/yourusername/TODO_LIST_PROJECT.git
cd TODO_LIST_PROJECT
pip install -r requirements.txt

