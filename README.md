Project Overview

This is the backend for my Better Assignment project.
It is built using Flask (Python) and provides REST API endpoints for managing comments.
The API supports operations like Add, Edit, Delete, and Fetch comments.


⚙️ Tech Stack

Python

Flask

SQLite / JSON for data storage

cURL for testing

🚀 How to Run

1.Clone the repository
git clone https://github.com/abhi-code26/Better-Assignment-task1.git
cd Better-Assignment-task1

2.Create virtual environment
python3 -m venv venv
source venv/bin/activate

3.Install dependencies
pip install -r requirements.txt

4.Run the app
python app.py

The backend will start at → http://127.0.0.1:5000

🔗 API Endpoints
| Method | Endpoint         | Description        |
| ------ | ---------------- | ------------------ |
| GET    | `/comments`      | Fetch all comments |
| POST   | `/comments`      | Add a new comment  |
| PUT    | `/comments/<id>` | Update a comment   |
| DELETE | `/comments/<id>` | Delete a comment   |

Video Demo
https://www.loom.com/share/854fdb8f61aa44399d49753f5a581e32
