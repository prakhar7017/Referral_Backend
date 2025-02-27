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

## How to Run  

### 1. Clone the repository  
```sh
git clone https://github.com/your-repo/linktree-backend.git
cd linktree-backend
python -m venv venv
source venv/bin/activate 
pip install -r requirements.txt
uvicorn app.main:app --host 0.0.0.0 --port 8000 --reload