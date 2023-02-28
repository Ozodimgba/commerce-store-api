# Commerce Store API

A simple ecommerce API

---

TASK DESCRIPTION

---

Build a simple ecommerce API with the following features:

1. Create, get all and get single product
2. Update product
3. Delete product
4. Simple pagination

---

## Tech Stack

- Node Js
- Typescript
- Express
- MongoDB
- Jest
- Postman

## Host Link

API Endpoint: [Production](https://commerce-api-production.up.railway.app/)

## Features

- Authentication and authorization
- CRUD opetaionss and pagination
- Admin users : Authorized to create, update and delete product

## Documentation

Postman: [See documentation]

## API Endpoints

Auth

```
POST /api/v1/auth/register
POST /api/v1/auth/login
```

Product

```
POST /api/v1/products
GET /api/v1/products
GET /api/v1/products/:productId
DELETE /api/v1/products/:productId
PATCH /api/v1/products/:productId
```

## Clone this project

```
git clone https://https://github.com/Ozodimgba/commerce-store-api.git
```

```
cd commerce-store-api
```

## Configure the app

- Create a file named `.env` in the project root directory
- Add the environment variables as described in the `dev.env` file

## Install dependencies

```
yarn install
```

## Running this project locally

```
yarn dev
```
