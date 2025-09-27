# 🎬 MovieFy

A full-stack movie platform with user and admin interfaces — featuring movie streaming, reviews, and content management — built with **React**, **Node.js**, and **MongoDB**.

## 🚀 Project Overview

**MovieFy** is a feature-rich movie application with two distinct portals: one for regular users and one for administrators.

- Users can stream movies, view cast and genre information, write reviews with star ratings, and toggle between light/dark modes and multiple languages.
- Admins can manage the movie database, including adding/editing movie entries and actor profiles.


## Installation

1. Clone The Repository:
    ```bash
    git clone https://github.com/GGurol/moviefy.git
    ```

2. Navigate to the project directory:
    ```bash
    cd moviefy
    ```

3. Build the docker:
    ```bash
    docker compose up --build -d
    ```

4. Login via : localhost:5173 with admin information in .env file.

(***) The MailHog service has been added for email operations. You can access the service at http://localhost:8025. 
A confirmation code will be sent here for the registration process 



## 🛠️ Tech Stack

| Layer        | Tools & Libraries                 |
| ------------ | --------------------------------- |
| **Frontend** | React, Tailwind CSS, shadcn/ui    |
| **Backend**  | Node.js, Express                  |
| **Database** | MongoDB                           |
| **Auth**     | JSON Web Tokens (JWT), Nodemailer |
| **i18n**     | react-i18next                     |
| **DevOps**   | Docker, Caddy                     |

## 📦 Development Process

1. **UI/UX Design** – Mocked responsive layouts for user and admin flows
2. **Frontend** – Built modular, styled interfaces with React and Tailwind
3. **Backend** – Created RESTful APIs to handle movies, actors, reviews
4. **Localization** – Integrated i18n with support for English and Chinese
5. **Deployment** – Dockerized the app and deployed using Caddy for reverse proxying and static serving

## 🌟 Key Features

### 🧑‍💻 User Side

- 🎞️ Stream movies and search by title
- 🧑‍🤝‍🧑 View detailed cast, genres, and related movies
- ⭐ Submit and read star-based reviews
- 🌙 Toggle dark/light themes
- 🌐 Switch between English and Chinese

### 🔧 Admin Side

- 🎬 Add/edit/delete movies with cover images and videos
- 🎭 Manage actor profiles with names and pictures
- 📝 Monitor user-submitted reviews and ratings




