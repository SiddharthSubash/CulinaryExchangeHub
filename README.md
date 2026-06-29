# Culinary Exchange Hub

A full-stack recipe-sharing web application where users can register, log in, create recipes, search recipes, update their profile, and manage their own dishes.

Built with Flask, PostgreSQL, psycopg2, HTML, CSS, JavaScript, and jQuery.

## Live Demo

[Open the live application](https://culinaryexchangehub.onrender.com)

> The live site is hosted on Render's free tier, so the first request after inactivity may take up to a minute.

## Features

- User registration and login
- Password reset
- User profile updates
- Recipe creation and editing
- Recipe search and display
- Personal “My Dishes” recipe management
- PostgreSQL-backed storage for users, recipes, ingredients, and preparation steps

## Technologies Used

- Python
- Flask
- PostgreSQL
- psycopg2
- HTML
- CSS
- JavaScript
- jQuery
- Render
- Neon PostgreSQL

## Architecture

```text
Browser
   ↓
Flask application hosted on Render
   ↓
psycopg2 and SQL queries
   ↓
Neon PostgreSQL database
```
