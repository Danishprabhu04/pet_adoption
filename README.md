🐾 Pet Adoption System
A full-stack web application that allows users to browse available pets, register as owners, request adoptions, and track the status of their adoption requests.

Tech Stack: Flask (Python) | HTML + Bootstrap | PostgreSQL

💡 Features
View available pets (with photos)

Register owners

Submit adoption requests

View request status

Admin login (with restricted access)

🚀 Setup
Set up Python virtual environment & install dependencies

Configure your PostgreSQL database and run schema SQL

Launch Flask backend (python app.py)

Open frontend using browser or http.server

📡 API Endpoints
Method	Endpoint	Description
GET	/pets	List pets
POST	/owners	Add owner
POST	/request	Request adoption
GET	/my_requests/<id>	View user requests
