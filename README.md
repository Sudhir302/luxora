# Luxora
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

*Luxora* is a full-stack e-commerce web application built using the *MERN* stack. It features a modern, responsive design with separate interfaces for customers and administrators. The application provides a seamless shopping experience with secure payment processing and efficient order management.

## ⚡ Features

### Customer Features
- User Authentication (Login / Signup)
- Product Browsing and Search
- Shopping Cart Management
- Secure Payment Processing (Stripe & Razorpay)
- Order History and Tracking
- Responsive Design for all devices
- Newsletter Subscription

### Admin Features
- Secure Admin Authentication
- Product Management (Add/Edit/Delete)
- Order Management
- Inventory Tracking
- Sales Analytics

## 🏗️ Project Structure
```
luxora/
├── frontend/          # Customer-facing React application
├── admin/            # Admin panel React application
└── backend/          # Node.js + Express server
```

## 👩‍💻 Technologies Used

### Frontend & Admin Panel
- React 18
- Vite
- React Router DOM
- TailwindCSS
- React Toastify
- Axios

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Bcrypt for Password Hashing
- Cloudinary for Image Storage
- Stripe & Razorpay for Payments
- Multer for File Uploads

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account
- Cloudinary account
- Stripe & Razorpay accounts (for payments)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/luxora.git
cd luxora
```

2. Install dependencies for all three applications:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

# Install admin panel dependencies
cd ../admin
npm install
```

3. Set up environment variables:
   - Create `.env` files in both frontend, admin, and backend directories
   - Add necessary environment variables (see .env.example files)

4. Start the development servers:
```bash
# Start backend server (from backend directory)
npm run dev

# Start frontend (from frontend directory)
npm run dev

# Start admin panel (from admin directory)
npm run dev
```

The applications will be available at:
- Frontend: http://localhost:5173
- Admin Panel: http://localhost:5174
- Backend API: http://localhost:3000

## 📁 Project Structure Details

### Frontend
```
frontend/
├── src/
│   ├── components/    # Reusable UI components
│   ├── pages/        # Page components
│   ├── context/      # React context providers
│   ├── assets/       # Static assets
│   └── utils/        # Utility functions
```

### Admin Panel
```
admin/
├── src/
│   ├── components/   # Admin UI components
│   ├── pages/        # Admin page components
│   └── utils/        # Utility functions
```

### Backend
```
backend/
├── controllers/      # Route controllers
├── models/          # Database models
├── routes/          # API routes
├── middleware/      # Custom middleware
└── utils/           # Utility functions
```

## 🔒 Environment Variables

### Backend (.env)
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

### Frontend (.env)
```
VITE_BACKEND_URL=http://localhost:3000
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

### Admin (.env)
```
VITE_BACKEND_URL=http://localhost:3000
```

## 🧣 Future Enhancements
- Implement real-time order tracking
- Add product reviews and ratings
- Integrate social media sharing
- Add wishlist functionality
- Implement advanced search filters
- Add multi-language support
- Implement push notifications

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 👥 Contact

For any queries or support, please reach out to:
- Email: csudhir302@gmail.com
- Phone: +91 9125137806