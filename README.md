# ruby-rails-coursera-unm

A **Ruby on Rails application** built as part of the **Coursera University of New Mexico course**.  
This project demonstrates key Rails concepts such as MVC structure, CRUD operations, database migrations, and RESTful routes.

---

## 🚀 Features

- User sign-up and login (authentication basics)  
- CRUD functionality for posts/articles  
- RESTful routes and controllers  
- Database migrations and seed data  
- JSON API endpoints (if applicable)

---

## 🛠 Tech Stack

- **Ruby:** 3.1.2  
- **Rails:** 7.0.x  
- **Database:** SQLite (development), PostgreSQL (production)  
- **Front-end:** ERB templates (default Rails views)  
- **Other tools:** Bundler, Yarn (for assets)

---

## ⚙️ Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/CelibethGM/ruby-rails-coursera-unm.git
cd ruby-rails-coursera-unm
```


2. **Set up the database**
```bash
rails db:create
rails db:migrate
rails db:seed   # optional, if seed data is provided
```

3. **Run the server**
```bash
rails server
```
Open http://localhost:3000 in your browser.


## Acknowledgments
Built as part of the Coursera: University of New Mexico Ruby on Rails course.