This is a simple application I created to demonstrate how to build full stack search using Next.js and Prisma. Please follow the below instructions to get the project up and running.

## Getting Started

### Install packages

```
npm i
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATABASE_URL="YOUR_POSTGRES_DATABASE_URI"`

### Run database migration

```
npx prisma migrate dev --name=init
```

### Seed the database with fake data (courtesy of ChatGPT)

```
npx prisma seed db
```

### Generate the Prisma client

```
npx prisma generate
```

### Start the development server

```
npm run dev
```
