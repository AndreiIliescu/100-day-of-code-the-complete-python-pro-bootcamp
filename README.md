# 100 Days of Code: The Complete Python Pro Bootcamp

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.11-blue)
![Progress](https://img.shields.io/badge/progress-100%2F100%20days-brightgreen)
![Course](https://img.shields.io/badge/course-Udemy-A435F0)
![Instructor](https://img.shields.io/badge/instructor-Angela%20Yu-orange)

A complete record of all 100 projects built during the [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) by Angela Yu on Udemy. Each day covers a new concept, a new challenge, and a new project — from Python basics to full-stack web development.

---

## Table of Contents

- [About](#about)
- [Certificate](#certificate)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Running Tests](#running-tests)
- [Project Structure](#project-structure)
- [Projects Overview](#projects-overview)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

This repository contains every project built across 100 days of the most comprehensive Python bootcamp available on Udemy. The course covers the full journey from Python fundamentals to production-ready backend development with Django, database integration with MySQL and PostgreSQL, frontend basics with HTML5, CSS3, and Vanilla JavaScript, and automated testing with PyTest.

The goal is not just to finish the course. The goal is to build real muscle memory for writing clean, working Python code every single day.

Each project folder is self-contained and includes its own code, any required assets, and a brief description of what was built and what concept it covers.

---

## Certificate

<!-- Replace the placeholder below with your actual Udemy certificate image or link once you complete the course -->

![Udemy Certificate of Completion](https://)

---

## Features

- 100 fully functional Python projects, one per day
- Covers Python 3.14.2, automation, web scraping, data science, GUI apps, and backend development
- Backend projects built with Flask and Django
- Database integration with MySQL and PostgreSQL
- Frontend projects using HTML5, CSS3, and Vanilla JavaScript
- Automated tests written with PyTest
- Clean project structure, with each day isolated in its own folder
- Environment variables managed via `.env` files for all projects that require them

---

## Tech Stack

- Python 3.14.2
- Flask
- Django 6.2
- MySQL 8.0
- PostgreSQL 15
- HTML5, CSS3, JavaScript (Vanilla)
- PyTest
- SQLAlchemy
- Pandas, NumPy, Matplotlib, Plotly
- Selenium WebDriver
- Beautiful Soup 4
- Tkinter
- Git and GitHub

---

## Getting Started

### Prerequisites

Make sure you have the following installed before running any project:

- Python 3.11+
- pip
- virtualenv or venv
- MySQL 8.0+ (for MySQL projects)
- PostgreSQL 15+ (for PostgreSQL projects)
- Google Chrome + ChromeDriver (for Selenium projects)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/AndreiIliescu/100-day-of-code-the-complete-python-pro-bootcamp.git
cd 100-day-of-code-the-complete-python-pro-bootcamp
```

2. Navigate to the specific day you want to run:

```bash
cd day-001
```

3. Create and activate a virtual environment:

```bash
python -m venv .venv

# macOS / Linux
source venv/bin/activate

# Windows - CMD
.\.venv\Scripts\activate

# Windows - PowerShell
.\.venv\Scripts\activate.ps1
```

4. Install the dependencies for that project:

```bash
pip install -r requirements.txt
```

5. Copy the environment variables template and fill in your values (for projects that need it):

```bash
cp .env.example .env
```

6. Run the project:

```bash
python main.py
```

For Flask or Django projects, see the specific instructions in each project's own `README.md`.

---

## Usage

Each day folder contains:

- `main.py` or the project entry point
- `requirements.txt` with project-specific dependencies
- `.env.example` (where applicable)
- A short `README.md` explaining the day's concept and how to run it

Example — running the Snake Game from Day 20:

```bash
cd day-020
python -m venv .venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```

Example — running the Blog Website from Day 69:

```bash
cd day-069
python -m venv venv
source venv/bin/activate                      # macOS / Linux
.\.venv\Scripts\activate                      # Windows - CMD
.\.venv\Scripts\activate.ps1                  # Windows - PowerShell
pip install -r requirements.txt
cp .env.example .env
flask run
```

---

## Environment Variables

Projects that connect to databases, APIs, or external services use a `.env` file. A `.env.example` file is included in each relevant project folder.

Common variables used across projects:

```env
SECRET_KEY=your_secret_key_here
DEBUG=True

DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=localhost
DB_PORT=5432

EMAIL_ADDRESS=your_email@example.com
EMAIL_PASSWORD=your_email_password

API_KEY=your_api_key_here
```

Never commit your actual `.env` file. The `.gitignore` already excludes it.

---

## Running Tests

Projects that include automated tests use PyTest.

To run tests for a specific project:

```bash
cd day-XXX
pytest
```

To run tests with coverage:

```bash
pytest --cov=. --cov-report=term-missing
```

---

## Project Structure

```
100-day-of-code-the-complete-python-pro-bootcamp/
,
+-- day-001/                  # Band Name Generator
+-- day-002/                  # Tip Calculator
+-- day-003/                  # Treasure Island (Control Flow)
+-- day-004/                  # Rock Paper Scissors
+-- day-005/                  # Password Generator
+-- ...
+-- day-020/                  # Snake Game (Turtle)
+-- day-021/                  # Snake Game: Score + High Score
+-- ...
+-- day-060/                  # Blog with Flask + WTForms
+-- day-061/                  # Flask Auth with hashing
+-- ...
+-- day-100/                  # Final Capstone Project
,
+-- .env.example
+-- .gitignore
+-- README.md
+-- LICENSE
```

---

## Projects Overview

| Day | Project | Topics Covered |
|-----|---------|---------------|
| 1 | Band Name Generator | Input, variables, print |
| 2 | Tip Calculator | Data types, math operators |
| 3 | Treasure Island | Conditional statements, logical operators |
| 4 | Rock Paper Scissors | Randomisation, lists |
| 5 | Password Generator | Loops, range, string manipulation |
| 6 | Reeborg's World | Functions, while loops |
| 7 | Hangman | Flow control, functions |
| 8 | Caesar Cipher | Functions with inputs, arguments |
| 9 | Silent Auction | Dictionaries, nesting |
| 10 | Calculator | Functions, recursion |
| 11 | Blackjack | OOP concepts, capstone |
| 12 | Number Guessing Game | Scope, global/local variables |
| 13 | Debugging Exercises | Debugging techniques |
| 14 | Higher Lower Game | Debugging, game logic |
| 15 | Coffee Machine | Local dev setup, IDE intro |
| 16 | OOP Coffee Machine | OOP: classes and objects |
| 17 | Quiz App | OOP, class methods |
| 18 | Hirst Painting | Turtle, importing modules |
| 19 | Turtle Race | Events, state |
| 20 | Snake Game Part 1 | Animation, coordinates |
| 21 | Snake Game Part 2 | Inheritance, list slicing |
| 22 | Pong Game | Multiple classes |
| 23 | Turtle Crossing | Game state management |
| 24 | Mail Merge | File I/O, reading and writing |
| 25 | US States Game | CSV + Pandas |
| 26 | NATO Phonetic Alphabet | List and dict comprehension |
| 27 | Miles to KM Converter | Tkinter GUI |
| 28 | Pomodoro Timer | Tkinter, dynamic UI |
| 29 | Password Manager | Tkinter, JSON, error handling |
| 30 | Password Manager v2 | Exception handling |
| 31 | Flash Card App | Tkinter capstone |
| 32 | Automated Birthday Emails | SMTP, datetime |
| 33 | ISS Overhead Notifier | API, requests |
| 34 | Quiz App from API | JSON, external APIs |
| 35 | Rain Alert SMS | Twilio API |
| 36 | Stock Trading Alert | News + Stock APIs |
| 37 | Habit Tracker (Pixela) | POST, PUT, DELETE requests |
| 38 | Workout Tracking | Nutritionix + Sheety APIs |
| 39 | Flight Deal Finder Part 1 | Sheety, Kiwi API |
| 40 | Flight Deal Finder Part 2 | Capstone project |
| 41 | Movie Rankings Webpage | HTML5 basics |
| 42 | Birthday Invite Page | HTML + CSS |
| 43 | CSS Color Vocab | CSS selectors, properties |
| 44 | Motivational Poster | CSS, Box Model |
| 45 | Top 100 Movies Scraper | BeautifulSoup, web scraping |
| 46 | Spotify Playlist Creator | Spotify API, scraping |
| 47 | Amazon Price Tracker | Selenium, scraping |
| 48 | Cookie Clicker Bot | Selenium automation |
| 49 | LinkedIn Job Application Bot | Selenium, forms |
| 50 | Tinder Auto Swiper | Selenium |
| 51 | Internet Speed Twitter Bot | Selenium |
| 52 | Instagram Follower Bot | Selenium |
| 53 | Data Entry Job Automation | Selenium + web forms |
| 54 | Flask Introduction | Flask routing, templates |
| 55 | Higher Lower Game in Flask | Flask, decorators |
| 56 | Name Card Website | HTML templates, Jinja2 |
| 57 | Blog with Flask | Jinja2, rendering |
| 58 | TinDog Bootstrap Site | Bootstrap, HTML, CSS |
| 59 | Blog with Forms | WTForms, POST requests |
| 60 | Blog with Contact Form | SMTP, Flask |
| 61 | Flask Auth + Hashing | Werkzeug, hashing |
| 62 | Coffee and Wi-Fi | Flask, SQLite, WTForms |
| 63 | Bookshelf App | Flask, SQLite, SQLAlchemy |
| 64 | My Top 10 Movies | SQLAlchemy, Movie DB API |
| 65 | Personal Blog | REST, Flask, JSON |
| 66 | REST API Cafe | Flask REST API |
| 67 | RESTful Blog | REST with Flask |
| 68 | Authentication with Flask | Flask-Login, hashing |
| 69 | Blog with Users | Relationships, DB |
| 70 | Git and GitHub | Version control |
| 71 | Data Exploration with Pandas | Pandas, Matplotlib |
| 72 | College Major vs Salary | Data analysis |
| 73 | LEGO Dataset Analysis | Pandas, data cleaning |
| 74 | Google Trends | Time series, resampling |
| 75 | Google Trends + Data Viz | Multi-axis charts |
| 76 | Google Play Store Analysis | Plotly, Pandas |
| 77 | Linear Regression | Scikit-learn, regression |
| 78 | Nobel Prize Analysis | Plotly, Seaborn |
| 79 | Computation with NumPy | NumPy arrays |
| 80 | Morse Code Converter | Python scripting |
| 81 | Text to Morse Audio | Scripting + audio |
| 82 | Typing Speed App | Tkinter, events |
| 83 | Tic Tac Toe | OOP, game logic |
| 84 | Image Watermarking App | Tkinter, Pillow |
| 85 | Turtle Crossing Capstone | OOP capstone |
| 86 | Breakout Game | OOP, animation |
| 87 | Cafe and Wi-Fi Website | Flask + Bootstrap |
| 88 | To Do List App | Flask, PostgreSQL |
| 89 | Disappearing Text App | Tkinter |
| 90 | PDF to Audiobook | pdfplumber, text-to-speech |
| 91 | Image Colour Palette | Colorgram, Flask |
| 92 | Custom Web Scraper | BeautifulSoup, Requests |
| 93 | Google Dinosaur Game Bot | Selenium |
| 94 | Space Invaders | Pygame or Turtle |
| 95 | Custom API | Flask REST API |
| 96 | Online Resume | HTML5, CSS3, Flask |
| 97 | Percentage Calculator | Django |
| 98 | Public API | Django REST Framework |
| 99 | Space Launch News | Django + external API |
| 100 | Final Capstone Project | Full-stack: Django + PostgreSQL + HTML/CSS/JS |

---

## Contributing

This is a personal learning repository. Contributions are not expected, but if you spot a bug or a better way to solve a challenge, feel free to open an issue or a pull request.

1. Fork the repository
2. Create a new branch: `git checkout -b fix/day-XXX-issue`
3. Commit your changes: `git commit -m "Fix: day XXX - describe what you fixed"`
4. Push: `git push origin fix/day-XXX-issue`
5. Open a Pull Request

---

## License

Distributed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

Andrei Iliescu

[![Email Outlook](https://img.shields.io/badge/Outlook-andrei.iliescu13102000%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:andrei.iliescu13102000@outlook.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Andrei_Iliescu-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrei-iliescu-aa7910214)

[![GitHub](https://img.shields.io/badge/GitHub-Andrei_Iliescu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AndreiIliescu)