# Flask Blog Application

## Project Description

This is a Flask web application that displays a list of blog posts and individual post details. The application fetches blog data from an API, processes it into objects using a custom `Post` class, and renders it using Flask templates.

## Features

1. **Homepage (`/`):**
   - Displays a list of all blog posts.
   - Renders `index.html` with all posts available in the `post_objects` list.

2. **Post Detail (`/post/<int:id>`):**
   - Displays details of a specific blog post based on its ID.
   - Renders `post.html` with the details of the requested post.

## Code Overview

- **`post.py`:** Contains the `Post` class definition.
- **`app.py`:** The main Flask application script that sets up routes and handles rendering of templates.
