# Backend, P1

A RESTAPI for creating, reading and updating orders

## Instructions

Move to the backend directory

```bash
cd backend
```

Install all required dependencies

```bash
npm install
```

Create a .env file: "/backend/.env"
Add the Database URI and PORT in this format:

```bash
PORT = 4000
DB_URI = "mongodb://localhost:27017/Orders"
```

## Run the server

run the following command

```bash
npm run dev
```

## API Endpoints

```bash
# ORDER ENDPOINTS

| HTTP Request |    Endpoint    |             Action            |
|:------------:|:--------------:|:-----------------------------:|
| GET          | /api/orders    | To view all orders            |
| POST         | /api/order/new | To create a new order         |
| PUT          | /api/order/:id | To update the status of order |


# PRODUCT ENDPOINTS

| HTTP Request |     Endpoint     |          Action          |
|:------------:|:----------------:|:------------------------:|
| GET          | /api/products    | To view all products     |
| POST         | /api/product/new | To create a new product  |


#TRIP ENDPOINTS

| HTTP Request |    Endpoint   |         Action        |
|:------------:|:-------------:|:---------------------:|
| GET          | /api/trips    | To view all trips     |
| POST         | /api/trip/new | To create a new trip  |

```


