# Alpha Blog

A simple blogging application built with Ruby on Rails to practice full CRUD functionality (Create, Read, Update, Delete). This project is part of learning Rails basics and follows the Alpha Blog tutorial.

## Features

- Create, read, update, and delete articles
- Flash messages for success/error notifications
- Validations on article fields
- RESTful routes (`resources :articles`)
- Server-rendered views using ERB templates

## Tech Stack

- Ruby on Rails (7.x)
- SQLite3 (development/test)
- PostgreSQL (production optional)
- Turbo / Hotwire for improved interactivity
- Bootstrap (optional, for styling)

## Quick Start

```bash
# Clone the repo
git clone https://github.com/your-username/alpha-blog.git
cd alpha-blog

# Install dependencies
bundle install

# Set up the database
rails db:create db:migrate

# Start the server
rails server

# Visit the server
http://localhost:3000
```
