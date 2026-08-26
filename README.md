# Music Streaming Microservices

A full-stack music streaming application built using React, TypeScript, Node.js, and a microservices architecture.

## Features

- User registration and login
- JWT authentication
- Browse songs and albums
- Play music
- Create and manage playlists
- Admin dashboard
- Add and delete songs
- Add and delete albums
- Redis caching
- Cloudinary media storage

## Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Node.js
- Express.js
- MongoDB
- PostgreSQL
- Redis
- Cloudinary
- JWT

## Project Structure

```text
music-streaming-microservices/
│
├── frontend/
├── user service/
├── song service/
├── admin service/
└── README.md

Microservices
User Service

Handles:

User registration
User login
Authentication
User information

Runs on:

http://localhost:5000

Song Service

Handles:

Songs
Albums
Song and album data
Redis caching

Runs on:

http://localhost:8000

Admin Service

Handles:

Adding songs
Adding albums
Deleting songs
Deleting albums
Media uploads

Runs on:

http://localhost:7000

Frontend

Built with React and TypeScript.

Runs on:

http://localhost:5173
Database
MongoDB is used for user data.
PostgreSQL is used for songs and albums.
Redis is used for caching.
Cloudinary is used for media storage.

Installation

Clone the repository:

git clone https://github.com/SunidhiVyas/music-streaming-microservices.git

Go to the project folder:

cd music-streaming-microservices

Install dependencies in each folder:

cd frontend
npm install
cd "../user service"
npm install
cd "../song service"
npm install
cd "../admin service"
npm install
Environment Variables

Create .env files for the User, Song, and Admin services.

Do not upload .env files to GitHub because they contain private credentials.

Running the Project

Start the User Service:

cd "user service"
npm run dev

Start the Song Service:

cd "song service"
npm run dev

Start the Admin Service:

cd "admin service"
npm run dev

Start the Frontend:

cd frontend
npm run dev

Then open:

http://localhost:5173