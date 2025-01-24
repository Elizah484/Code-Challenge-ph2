# Simple E-Commerce Cart 

## Introduction
This project is a *Simple E-Commerce Cart application* built using React. It allows users to browse a list of products, add them to a cart, modify cart contents, and view a total price. The app demonstrates core concepts of React such as components, props, state, events, and data management.

---

## Features

### Core Features:
- Display a list of products with their names, prices, and an "Add to Cart" button.
- Add products to the cart, increasing their quantity if already present.
- View a list of all cart items with names, prices, quantities, and total price.
- Remove items from the cart or adjust their quantities.

## Project Setup

### Prerequisites:
- Node.js and npm installed on your machine.

### Steps:
1. *Create a New React Project*:
   bash
   npx create-react-app ./

   
2. *Initialize Git Repository*:
   bash
   git init
   git remote add origin <your-repository-url>
   
3. *Add Sample Data*:
   Use the following sample product data:From the Code Challenge.
   json
   [
     { "id": 1, "name": "T-Shirt", "price": 20 },
     { "id": 2, "name": "Jeans", "price": 40 },
     { "id": 3, "name": "Sneakers", "price": 60 },
     { "id": 4, "name": "Hat", "price": 15 },
     { "id": 5, "name": "Socks", "price": 5 }
   ]
   
4. *Install Dependencies*:
   bash
   npm install
   
5. *Start Development Server*:
   bash
   npm start - starts the server
   
## Project Structure

.
├── public
├── src
│   ├── components
│   │   ├── ProductList.jsx
│   │   ├── Cart.jsx
│   │   ├── CartItem.jsx
│   │   └── Product.jsx
            Product.css
            ProductList.css
            Cart.css
            CartItem.css
│   ├── App.js
│   ├── App.css
│   └── index.js
├── package.json
└── README.md

## How to Use

1. *Browse Products*:
   View the list of products displayed on the main page with their names, prices, and "Add to Cart" buttons.

2. *Add to Cart*:
   Click the "Add to Cart" button for a product. If the product is already in the cart, its quantity increases.

3. *View Cart*:
   The cart displays all added products, showing their names, prices, quantities, and the total price.

4. *Modify Cart*:
   Adjust the quantity of any product in the cart or remove it entirely.

## Technologies Used
- React
- JavaScript 
- CSS

## Contributing
1. Fork the repository.
2. Create a new branch for your feature: git checkout -b feature-name.
3. Commit your changes: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature-name.
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
Phone number 0737908583
Email me at elizahwambosha@gmail.com
