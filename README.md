# Simple CRUD Application with Rails 7 and Devise

## Overview

This is a basic CRUD (Create, Read, Update, Delete) application built with Ruby on Rails 7, featuring user
authentication managed by Devise. The application allows users to register, log in, and manage a list of friends. Users
can create, view, edit, and delete friends, but can only modify friends that they themselves have created.

## Live Demo

Watch a live demo of the application
here: [Demo Video](https://www.loom.com/share/91d4de867da24b0b8f854cc4a9e10dff?sid=2e24e3e4-b92a-4ca5-853a-d68f88563874)

### Prerequisites

- Ruby 3.2+
- Rails 7+
- Node.js (for managing JavaScript dependencies)
- Yarn (optional, for managing JavaScript dependencies)
- SQLite (or any other database supported by Rails)

### Steps to Set Up the Application

   ```bash
   git clone ....

   bundle install

rails db:create
rails db:migrate
rails db:seed

rails server
```

Open your browser and visit http://localhost:3000 to view the application.
