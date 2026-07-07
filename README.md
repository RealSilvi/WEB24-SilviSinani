# 🐾 Social Network for Pets

A full-stack social network prototype inspired by platforms such as Instagram and Facebook, developed as part of the **Web Technologies** course at the **University of Bologna**.

The application allows users to register, create image-based posts, follow other users, interact through comments and likes, and explore/search profiles.

---

## 🚀 Features

- User registration and authentication
- Post creation with text and images
- Follow/unfollow system
- Comments and likes on posts
- User explore/search functionality
- Responsive interface built with Blade, Tailwind CSS and Alpine.js

---

## 🧩 Implementation Highlights

- Built with Laravel using an MVC-based structure
- Backend logic for users, posts, follows, comments and likes
- Database-backed entities and relationships
- Form handling and validation for user-generated content
- Blade views and reusable frontend components
- TypeScript and Alpine.js for interactive UI behavior
- Styling and layout implemented with Tailwind CSS

---

## 🛠 Tech Stack

- **Backend:** PHP, Laravel
- **Frontend:** Blade, HTML, TypeScript, Alpine.js
- **Styling:** Tailwind CSS
- **Database:** MySQL
- **Tooling:** Composer, PNPM, Vite

---

## 📦 Installation

Clone the repository and install the required dependencies.

```bash
composer install
pnpm install
```

Create the environment file:

```bash
cp .env.example .env
php artisan key:generate
```

Configure the database connection inside `.env`, then run:

```bash
php artisan migrate
```

If the project uses locally stored uploaded images, run:

```bash
php artisan storage:link
```

Start the frontend development server:

```bash
pnpm dev
```

Run the Laravel application:

```bash
php artisan serve
```

Then open the local application URL shown in the terminal.

---

## 🧪 University Setup Note

The original university development setup used the following local domain:

```text
http://web24-silvisinani.test
```

When running the project locally, make sure the `APP_URL` value in `.env` matches your development environment.

---

## 👨‍💻 Author

**Silvi Sinani**  
GitHub: [github.com/sinanisilvi](https://github.com/sinanisilvi)
