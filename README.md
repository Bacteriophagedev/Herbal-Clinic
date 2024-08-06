This project is aimed at showcasing CRUD operations using REST API's to perform tasks such as fetching doctor and Report data making minor and major updates and also deleting from the mongoDB databse using Mongoose.

To start the app you run yarn to install dependecies and generate yarn lock
add a .env file which will contain enviromental variables for the app: use the example below for reference

PORT = "3000" \\ Port number
NODE_ENV = "development" \\ develoypment environment
DATABASE_URL = "YOUR DATABASE URL"\\ You can get a database connection string from mongoDB cloud
DATABASE_PASSWORD = "YOUR DATABASE PASSWORD" \\ password to the databaseyou set up on MongoDb cloud
secret = "ANY STRING OF YOUR CHOICE" this will serve as you JWT secret Key
