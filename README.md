# Running the project

## Install necessary packages at Frontend and Backend
 Run _npm i_ at /client and /server directories
> npm i

## Create Database using PGAdmin
 Create a database at pgadmin and add that in database URL at .env file
> postgresql://postgres:**_username_**@localhost:5432/**_your_database_name_**?schema=public

 Migrate the database using ORM at /server
> npx prisma migrate dev --name init
> npx prisma generate
> Add .env file at root at /server

## Run Backend
> npm run start:dev

## Run Frontend
> npm run dev