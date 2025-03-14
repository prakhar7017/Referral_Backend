# Backend with Referral System

## Overview
This project is a backend system built with **FastAPI** and **PostgreSQL**, supporting user authentication, a referral system, and secure password management.

## Tech Stack
- **Backend Framework:** FastAPI (Python)  
- **Database:** PostgreSQL  
- **Authentication:** JWT (JSON Web Tokens)  
- **Security:** bcrypt for password hashing, OAuth2 for authentication  
- **Caching:** Redis (optional)  
- **Testing:** Pytest  

## 📌 **API Documentation**  
The API is documented in Postman. You can access the full API documentation using the link below:  

🔗 **[Postman Documentation](https://documenter.getpostman.com/view/24274037/2sAYdhHV3L)** 

## How to Run  

### 1. Clone the repository  
```sh
git clone https://github.com/prakhar7017/Referral_Backend.git
cd linktree-backend
python -m venv venv
source venv/bin/activate 
pip install -r requirements.txt
uvicorn app.main:app  --reload




