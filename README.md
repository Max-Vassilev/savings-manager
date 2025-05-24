# Savings Manager

A full-stack finance app for setting and managing savings goals, tracking progress through manual entries. Built to demonstrate full-stack development practices.

## Features

- User registration, login, and logout  
- Set your savings goal and preferred currency  
- Input your initial savings amount  
- Log a deposit to increase your savings  
- Log a withdrawal to decrease your savings  
- Dashboard displays current balance, goal progress, and recent activity  
- Shows the last 10 logged deposits and withdrawals  
- Notifies users upon reaching their goal and offers the option to reset or update it

## Tech Stack

- **Frontend:** React  
- **Backend:** Django REST API  
- **Database:** PostgreSQL  
- **Containers:** Docker & Docker Compose  
- **CI:** GitHub Actions for automated testing

This project highlights full-stack development combined with containerization and continuous integration.

## API Endpoints

- `POST /user/register/` – Register user  
- `POST /user/login/` – Login user  
- `POST /user/logout/` – Logout user  
- `POST /api/goal/` – Set savings goal and initial amount  
- `POST /api/deposit/` – Log a deposit (increase savings)  
- `POST /api/withdrawal/` – Log a withdrawal (decrease savings)  
- `GET /api/home/` – Get current balance, goal progress, and recent activity  
