# Long E-commerce

A modern e-commerce platform for handmade bags, clothes, and accessories.

## Features

- User authentication and authorization
- Product catalog with categories
- Featured products section
- Shopping cart functionality
- Secure payment processing
- User profile management
- Admin dashboard for product management

## Tech Stack

- Backend: Node.js, Express.js, MongoDB
- Frontend: React.js
- Authentication: JWT
- Payment Processing: Stripe

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/long-ecommerce.git
cd long-ecommerce
```

2. Install dependencies:
```bash
npm install
```

3. Create a .env file in the root directory with the following variables:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/long-ecommerce
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
```

4. Start the development server:
```bash
npm run dev
```

The server will start on http://localhost:5000

## API Endpoints

### Products
- GET /api/products - Get all products
- GET /api/products/featured - Get featured products
- GET /api/products/category/:category - Get products by category
- GET /api/products/:id - Get single product
- POST /api/products - Create new product (admin only)
- PUT /api/products/:id - Update product (admin only)
- DELETE /api/products/:id - Delete product (admin only)

### Users
- POST /api/users/register - Register new user
- POST /api/users/login - Login user
- GET /api/users/profile - Get user profile
- PUT /api/users/profile - Update user profile

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
