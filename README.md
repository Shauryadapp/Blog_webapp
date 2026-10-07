# Blog_webapp

A lightweight, server-rendered blog web application built using **FastAPI**, **Jinja2 templates**, and vanilla **HTML/CSS**.

---

## Features

- **FastAPI Backend:** High-performance, asynchronous routing and data validation.
- **Server-Side Rendering:** HTML page rendering powered by Jinja2 templates.
- **Static Asset Management:** Modular CSS styling and static files served directly via FastAPI.
- **Schema Validation:** Data models defined and structured with Pydantic (`schemas.py`).
- **Interactive API Docs:** Built-in Swagger UI documentation out of the box.

---

## Project Structure

```text
Blog_webapp/
│
├── static/              # Static files (CSS stylesheets, images, scripts)
├── templates/           # Jinja2 HTML templates
├── main.py              # Application entry point and route definitions
├── schemas.py           # Pydantic models for data validation
├── requirements.txt     # Python project dependencies
├── snippets.txt         # Code snippets and reference notes
└── README.md            # Project documentation
