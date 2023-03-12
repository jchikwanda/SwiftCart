# SwiftCart

SwiftCart is a MERN stack e-commerce website that allows users to browse and purchase products online. The website includes user authentication, product listings, a shopping cart, checkout process, order history, and an admin dashboard for managing products, orders, and users.

## Technologies Used

- React.js
- Redux
- Node.js
- Express.js
- MongoDB
- Stripe

## Getting Started

To get started with SwiftCart, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `npm install`.
3. Create a `.env` file in the `server` directory and set the following environment variables:

```
MONGODB_URI=<your MongoDB connection URI>
STRIPE_SECRET_KEY=<your Stripe secret key>
```


4. Start the development server for the client side using `npm start` from the `client` directory.
5. Start the Express.js server using `npm start` from the `server` directory.
6. Navigate to `http://localhost:3000` in your web browser to view the website.

## Features

- User authentication: Users can create an account, log in, and log out. Admin users have access to an admin dashboard.
- Product listings: Products are displayed on the website, along with details such as price, description, and images. Products can be filtered by category or searched by name.
- Shopping cart: Users can add products to their shopping cart, view the contents of their cart, and update the quantities of items.
- Checkout process: Users can enter their shipping and payment information to complete the checkout process. Payment processing is handled using Stripe.
- Order history: Users can view their order history and the status of their current orders.
- Admin dashboard: Admin users can manage products, orders, and users. They can add, edit, or delete products and view or update order details.

## Project Structure

The project structure is as follows:

```
├── client
│ ├── public
│ ├── src
│ │ ├── actions
│ │ ├── components
│ │ ├── constants
│ │ ├── reducers
│ │ ├── screens
│ │ ├── utils
│ │ ├── App.js
│ │ ├── index.js
│ ├── package.json
│ ├── ...
├── server
│ ├── controllers
│ ├── models
│ ├── routes
│ ├── config.js
│ ├── server.js
│ ├── package.json
│ ├── ...
├── README.md
```


The `client` directory contains the React.js client-side code, while the `server` directory contains the Node.js and Express.js server-side code.

## Contributing

Contributions are welcome! To contribute to SwiftCart, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make changes and commit them.
4. Push your changes to your fork.
5. Create a pull request.

## License

SwiftCart is licensed under the [MIT License](https://opensource.org/licenses/MIT).
