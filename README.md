 🔐 User Authentication System (FastAPI + MSSQL)

A secure user authentication backend built using **FastAPI** and **MSSQL** with features like JWT-based login, OTP password reset, and role-based access control.

 📌 Features
- User registration and login
- JWT authentication with token expiry
- Role-based access control
- Forgot password with OTP via email
- MSSQL backend with SQLAlchemy ORM

 🧰 Tech Stack
- **Backend**: FastAPI, Python 3.10
- **Database**: MSSQL Server, SQLAlchemy
- **Security**: JWT, Pydantic validation
- **Tools**: Git, VS Code

 🚀 How to Run
1. Clone the repo  
   ```bash
  git clone https://github.com/gopimuthukumar/user-auth-system.git
   cd user-auth-system
2.Install dependencies
  pip install -r requirements.txt
3.Set up MSSQL database and configure database.py
4.Run the app
 uvicorn main:app --reload

📁 Folder Structure
.
├── main.py
├── models/
├── routes/
├── utils/
├── database.py
├── requirements.txt

📝 Author
[Gopi Muthukumar](https://github.com/gopimuthukumar)

