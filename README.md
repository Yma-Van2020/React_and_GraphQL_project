# What are we building?

This is a simplified version of Product Hunt. Product Hunt is a website where individuals and companies can launch new products. 

Product Hunt users can share information about new products, vote for products they like, and discuss shared products. Our simplified version will contain only these three types of objects:

**Products**: Products are what users of Product Hunt share with the rest of the community. Each product will have a name, description, URL, and a number of upvotes.

**Categories**: Each product can belong to one or multiple categories, like SaaS or Productivity.

**Users**: Each product is shared by a specific user.

This is a full-stack application with a frontend, backend, and persistence layer.

## How to run the demo app

Running the server
First, you need to install server dependencies

```
cd server
npm install
```

Then you need to start Mongo database:

# In the "server" folder

```
npm run db:up
```
You need to keep it running, while you are working with the demo application.

Optionally, you can replace data in your database with the seed data using db:seed command:

# In the "server" folder

```
npm run db:seed
```

Once you have the database up and running, you can start the server using the following command:

# In the "server" folder

```
npm start
Running the client
```

First, you need to install client dependencies

```
cd client
npm install
```

Once you have the dependencies installed and the server running, run the following command to start the client:

# In the "client" folder
```
npm start
```
