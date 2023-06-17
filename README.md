#### cow-hut server

All Routes for Cow-Hut-Server

### Live Link(vercel): https://cow-hut-ten.vercel.app/

### Github Repository Link: https://github.com/Programming-Hero-Web-Course4/l2a3-cow-hut-backend-assignment-hasibul1670/tree/master

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

- https://cow-hut-ten.vercel.app/api/v1/auth/signup/seller [create/signup a seller] (POST)
- https://cow-hut-ten.vercel.app/api/v1/auth/signup/buyer [create/signup a buyer] (POST)
- https://cow-hut-ten.vercel.app/api/v1/users [get all users] (GET)
- https://cow-hut-ten.vercel.app/api/v1/users/648c804f7a84270cec0b4549 (get Single user) (GET)
- https://cow-hut-ten.vercel.app/api/v1/users/648c80897a84270cec0b4569 (Update Single user) (PATCH)

- https://cow-hut-ten.vercel.app/api/v1/users/648d41811747a704e729e0ea (Delete Single user ) (DELETE)

#### Buyer

- https://cow-hut-ten.vercel.app/api/v1/buyers [get all users] (GET)
- https://cow-hut-ten.vercel.app/api/v1/buyers/648c804e7a84270cec0b4546 (get Single Buyer) (GET)
- https://cow-hut-ten.vercel.app/api/v1/buyers/648c804e7a84270cec0b4546 (Update Single Buyer) (PATCH)

#### Seller

- https://cow-hut-ten.vercel.app/api/v1/sellers [get all users] (GET)
- https://cow-hut-ten.vercel.app/api/v1/sellers/648c80887a84270cec0b4566 (get Single Seller) (GET)
- https://cow-hut-ten.vercel.app/api/v1/sellers/648c80887a84270cec0b4566 (Update Single Seller) (PATCH)

#### Cows

- https://cow-hut-ten.vercel.app/api/v1/cows/create-cow [create a cow] (POST)
- https://cow-hut-ten.vercel.app/api/v1/cows [get all cows] (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows/648ca42c17d2d4e64a734513 [create a single cow] (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows/648ca42c17d2d4e64a734513 [Update a single cow] (PATCH)
- https://cow-hut-ten.vercel.app/api/v1/cows/648ca42c17d2d4e64a734513 [Delete a single cow] (DELETE)

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

- https://cow-hut-ten.vercel.app/api/v1/cows?page=1&limit=3 (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows?sortBy=price&sortOrder=asc (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows?minPrice=20000&maxPrice=70000 (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows?location=Chattogram (GET)
- https://cow-hut-ten.vercel.app/api/v1/cows?searchTerm=Cha (GET)

#### Orders

- http://localhost:5000/api/v1/orders [create order] (POST)
- http://localhost:5000/api/v1/orders [Get all Uers ] (GET)

### Sample Cow Order Data to create a Order

```json
{
  "cow": "648dbe893f8caeacd1d92178",
  "buyer": "648dbdd53f8caeacd1d92154"
}
```

```

```
# my-hut-ecom
