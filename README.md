# ShopPlusPlus

ShopPlusPlus is a e-commerce web application that provide a seamless shopping experience and streamline business operations online.

---

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

---

## Usage

- Create a MongoDB database and obtain your MongoDB URI - MongoDB Atlas
- Create a PayPal account and obtain your Client ID - PayPal Developer

### Env Variables

```bash
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = "arvind135"
PAYPAL_CLIENT_ID = your paypal client id
PAGINATION_LIMIT = 8
```

Change the JWT_SECRET and PAGINATION_LIMIT to what you want

### Install Dependencies(frontend & backend)

```bash
npm install
cd frontend
npm install
```

### Run

```bash
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

---

## Build & Deploy

```bash
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```bash
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```

```bash
Sample User Logins

admin@gmail.com (Admin)
12345

arvind@Gmail.com (Customer)
12345

```

### Deployment Link : https://shopcruise.onrender.com
