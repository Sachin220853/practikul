# Praktikul

Praktikul is a lightweight student learning and practice platform built using HTML, CSS, and JavaScript. It includes a landing page, signup flow, learning dashboard, aptitude practice, coding exercises, and a performance report view.

## Features

- Landing page with a modern hero design
- Student signup form
- Personalized dashboard with saved user details
- Aptitude practice section
- Technical and coding practice pages
- Performance report tracking page
- Local storage-based demo persistence for a static web app

## Project Structure

- `index.html` — landing page
- `signup.html` — signup / onboarding page
- `home.html` — dashboard after login
- `aptitude.html` — aptitude practice area
- `technical.html` — technical interview practice
- `coding-practice.html` — coding practice page
- `coding-quiz.html` — coding quiz page
- `python-coding.html` — Python coding practice page
- `performance-report.html` — score and progress summary

## Run Locally

Because this project is a static website, you can open the files directly in a browser.

For a local server:

```bash
python -m http.server 8000
```

Then open:

```bash
http://localhost:8000/
```

## Notes

- The app uses browser `localStorage` for demo user data.
- This is a front-end project and does not include a backend or database.
- It is designed for learning, UI practice, and demo purposes.

## License

This project is currently unlicensed.
