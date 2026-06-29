# Culinary Exchange Hub

This is the original Flask + psycopg2 project, prepared for hosting with minimal changes. The routes, templates, JavaScript, and database helper modules remain in the original structure.

## Local run

1. Create the `users` PostgreSQL database as before.
2. Copy `.env.example` to `.env` and update values only if necessary.
3. Install packages: `pip install -r requirements.txt`
4. Run: `python app.py`
5. Open `http://127.0.0.1:5500`

## Put it online (Render example)

1. Upload this project to a GitHub repository. Do not upload `.env`.
2. In Render, create a PostgreSQL database and copy its **Internal Database URL**.
3. Create a new Web Service from the repository.
4. Build command: `pip install -r requirements.txt`
5. Start command: `gunicorn app:app`
6. Add environment variables:
   - `DATABASE_URL`: the PostgreSQL URL from Render
   - `SECRET_KEY`: a long random string
   - `PGSSLMODE`: `require`
7. Deploy. Render gives your application a public `https://...onrender.com` URL.

## Important

The project uses the same plain-text password design as the original code. This is acceptable only as an academic demo. Do not use it with real user passwords.
