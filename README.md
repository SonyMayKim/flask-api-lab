📌 Flask REST API Lab

This project is a simple RESTful API built using Flask.
It demonstrates route creation, HTTP methods, error handling, and basic CRUD operations.

🚀 Features:
-  Basic Flask setup
-  REST API routes
-  Query parameter handling
-  UUID-based lookup
-  Add and delete operations
-  Error handling (404, 500, 422)
-  JSON responses

📂 Project Structure:
flask-api-lab/
│
├── server.py              # Main Flask application
├── requirements.txt    # Dependencies
└── README.md           # Project documentation

⚙️ Installation(<Bash>)
  1. Clone repository
      git clone https://github.com/YOUR_USERNAME/flask-api-lab.git
      cd flask-api-lab
  2. Create virtual environment (optional)
      python3 -m venv venv
      source venv/bin/activate
  3. Install dependencies
      pip install -r requirements.txt

▶️ Run the application
  Bash:
      python3 app.py
  Then open in browser:
      http://127.0.0.1:5000/

📡 API Endpoints
  Home
      GET /
  Get data count
      GET /count
  Search by name
      GET /name_search?q=keyword
  Get all data message
      GET /data
  Get person by UUID
      GET /person/<uuid:id>
  Delete person
      DELETE /person/<uuid:id>
  Add person
      POST /person
      Content-Type: application/json

❗ Error Handling:
      400 → Missing or invalid input
      404 → Resource not found
      422 → Validation error
      500 → Server error

🧠 What I learned: 
-  Flask routing
-  HTTP methods (GET, POST, DELETE)
-  Request handling
-  JSON responses
-  Error handling in Flask
