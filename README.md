# Usage

Create a MongoDB database and obtain your MongoDB URI - MongoDB Atlas
Create a PayPal account and obtain your Client ID - PayPal Developer
Env Variables

Rename the .env.example file to .env and add the following

NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
PAGINATION_LIMIT = 8
Change the JWT_SECRET and PAGINATION_LIMIT to what you want

Install Dependencies (frontend & backend)

npm install
cd frontend
npm install
Run


# Run frontend (:3000) & backend (:8000)
npm run dev

# Run backend only
npm run server
Build & Deploy

# Create frontend prod build
cd frontend
npm run build
Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

# Import data
npm run data:import

# Destroy data
npm run data:destroy
