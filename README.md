Running the server
First, you need to install server dependencies

cd server
npm install
Then you need to start Mongo database:

# In the "server" folder
npm run db:up
You need to keep it running, while you are working with the demo application.

Optionally, you can replace data in your database with the seed data using db:seed command:

# In the "server" folder
npm run db:seed
Once you have the database up and running, you can start the server using the following command:

# In the "server" folder
npm start
Running the client
First, you need to install client dependencies

cd client
npm install
Once you have the dependencies installed and the server running, run the following command to start the client:

# In the "client" folder
npm start