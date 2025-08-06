# Odinstagram

An Instagram‑inspired social media app built with Express, Prisma (PostgreSQL), and React.

## Live

https://odinsta-gram.netlify.app

Frontend deployed on Netlify  
Backend hosted on Railway

## Features

- Create Account and generate jsonwebtoken to authenticate routes
- Customize all profile information and profile picture, stored using Multer middleware
- Create Post's with images and text content
- Send follow requests to other users that they can accept or decline
- Have a feed of your and your follwing's posts
- Like and comment on posts
- View profiles and individual posts

## Installation

1. `git clone git@github.com:GrantRoots/odinstagram.git`
2. `cd odinstagram/api`
3. `npm install`
4. `npm run build`
5. `npm run seed` (Optional)
6. `npm run dev`

- Open new terminal window for the frontend

1. `cd odinstagram/frontend`
2. `npm install`
3. `npm run dev`

## Environment Variables

```
DATABASE_URL="your db url"
JWT_SECRET="secret"
TEST_DATABASE_URL="test db url"
NODE_ENV=development - or test
VITE_API_URL="http://localhost:3000" - Backend url for frontend API calls
```
