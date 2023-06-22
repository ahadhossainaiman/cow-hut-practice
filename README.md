### cow-hut server

All Routes for Cow-Hut-Server

### Live Link(vercel): https://digital-cow-hut-backend-assignment-seven.vercel.app/

### Github Repository Link: https://github.com/Programming-Hero-Web-Course4/l2a3-cow-hut-backend-assignment-ahadhossainaiman

### Application Routes:

### Sample User(Seller/Buyer) Post json type

```json
{
  "seller": {
    "name": {
      "firstName": "luka",
      "lastName": "mia"
    },
    "phoneNumber": "+1 123-456-7890",
    "address": "123 Main St, cumilla, dhaka",
    "income": 1000
  }
}
```

#### User

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/auth/signup/seller [create/signup a seller] (POST)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/auth/signup/buyer [create/signup a buyer] (POST)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/users [get all users] (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/users/648e081e45319758efe5d4e0(get Single user) (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/users/648e081e45319758efe5d4e0 (Update Single user) (PATCH)

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/users/648e081e45319758efe5d4e0(Delete Single user ) (DELETE)

#### Buyer

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/buyers [get all users] (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/buyers/648c804e7a84270cec0b4546 (get Single Buyer) (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/buyers/648c804e7a84270cec0b4546 (Update Single Buyer) (PATCH)

#### Seller

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/sellers [get all users] (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/sellers/648e019208dc72b6a4245419(get Single Seller) (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/sellers/648e019208dc72b6a4245419 (Update Single Seller) (PATCH)

#### Cows

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows/create-cow [create a cow] (POST)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows [get all cows] (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows/648e0d23f636612c843252f9 [create a single cow] (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows/648e0d23f636612c843252f9 [Update a single cow] (PATCH)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows/648e0d23f636612c843252f9 [Delete a single cow] (DELETE)

### Sample Cow Data for create a cow

```json
{
  "name": "king",
  "age": 4,
  "price": 17800,
  "location": "Dhaka",
  "breed": "Brahman",
  "weight": 400,
  "label": "for sale",
  "category": "Beef",
  "seller": "648dbc743f8caeacd1d9211e"
}
```

### Pagination and Filtering routes of Cows (GET)

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows?page=1&limit=3 (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows?sortBy=price&sortOrder=asc (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows?minPrice=20000&maxPrice=70000 (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows?location=Chattogram (GET)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/cows?searchTerm=Cha (GET)

#### Orders

- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/orders [create order] (POST)
- https://digital-cow-hut-backend-assignment-seven.vercel.app/api/v1/orders [Get all Uers ] (GET)

### Sample Cow Order Data to create a Order

```json
{
  "cow": "648dbe893f8caeacd1d92178",
  "buyer": "648dbdd53f8caeacd1d92154"
}
```

```

```

