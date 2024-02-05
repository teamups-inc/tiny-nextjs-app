# Tiny NextJS App

## Intro

Built with `create-next-app`, this is a super simple NextJS app that uses MongoDB for the database and is containerized to run using Docker compose.

## Quick start

1. Clone the repo: `git clone https://github.com/teamups-inc/tiny-nextjs-app.git`

2. CD into the repo: `cd /path/to/tiny-nextjs-app`

3. [Option 1: Docker] Start via docker compose: `docker-compose up`. [Option 2: NPM] Create a `.env` file at the root level of the repo with the following contents: "MONGODB_URI=mongodb://localhost:27017/". Run MongoDB locally on the default port, then start the app via `npm run dev`.

4. Once running, visit `http://localhost:3000/` to load the app--the first load might be slow. You should see the following page if everything is successful:
   <img width="1520" alt="Screenshot 2023-09-05 at 9 54 13 AM" src="https://github.com/teamups-inc/tiny-nextjs-app/assets/24460948/d80b1f61-9ac7-43af-a9e2-24862216338a">
