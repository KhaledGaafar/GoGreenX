# Green Living Hub

A web application for tracking personal health metrics and sustainability habits, built with Django (backend) and React (frontend).

# Features
# Health Tracking:
      . Log daily nutrition (calories, macros)
      
      . Record physical activity and workouts
      
      . Ask Ai to get a good plan
      
      . Join a community to exchange healthy ideas and encourage each other
# Technologies Used
Django REST Framework

PostgreSQL database

JWT Authenticati

Signals

 React.js

## Setup

### Backend
1. Navigate to `backend/`.
2. Create virtual environment: `python -m venv venv`.
3. Activate: `source venv/bin/activate`.
4. Install dependencies: `pip install -r requirements.txt`.
5. Create `.env` with secrets.
6. Run migrations: `python manage.py migrate`.
7. Start server: `python manage.py runserver`.

### Frontend
1. Navigate to `frontend/`.
2. Install dependencies: `npm install`.
3. Create `.env` with `VITE_API_URL`.
4. Start dev server: `npm run dev`.

## Team Workflow
- Feature branches: `feature/<name>`.
- PRs require one reviewer.
- Track tasks in [Trello/GitHub Projects].

## License
MIT
