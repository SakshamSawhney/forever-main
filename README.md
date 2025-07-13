# E-Commerce Website (MERN Stack)

## Description
This project is a fully functional e-commerce website built using the MERN (MongoDB, Express, React, Node.js) stack. It features user authentication, product management, a shopping cart, order placement, and payment gateway integration. The admin dashboard allows for efficient store management, including order tracking and product uploads.

## Features
- **Frontend**: Built with Vite React, including pages for home, collections, product details, cart, orders, login, about, and contact.
- **Backend**: Node.js and Express handle APIs, user authentication, and database management.
- **Authentication**: Secure user and admin authentication using JWT.
- **Product Management**: Upload, edit, and delete products via an admin dashboard.
- **Cart & Order Management**: Add products to the cart, place orders, and track them in the admin panel.
- **Payment Integration**: Supports Stripe and Razorpay for secure transactions.
- **Image Uploads**: Uses Cloudinary and Multer for efficient image storage and handling.
- **Deployment**: Fully deployed on Vercel for easy access.

## Project Structure
1. **Frontend**: Vite React setup, routing, and UI components.
2. **Backend**: API development with Express and MongoDB.
3. **Authentication**: User registration and admin verification.
4. **Product Features**: Uploading and displaying products.
5. **Cart & Orders**: Managing user purchases and tracking orders.
6. **Admin Dashboard**: Overview and control over website operations.
7. **Payments**: Secure integration with Stripe and Razorpay.
8. **Image Uploads**: Implemented using Cloudinary and Multer.
9. **Deployment**: Final hosting on Vercel.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SakshamSawhney/forever-main.git
   ```
2. Navigate to the project directory:
   ```bash
   cd forever-main
   ```
3. Install dependencies for both frontend and backend:
   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   cd ../admin
   npm install
   ```

4. Create .env files:
   ```bash
   .env in frontend
      VITE_BACKEND_URL = "http://localhost:4000"
   .env in backend
      MONGODB_URI = "<your mongo atlas uri>"
      CLOUDINARY_API_KEY="<your_CLOUDINARY_API_KEY>"
      CLOUDINARY_SECRET_KEY="<your_CLOUDINARY_SECRET_KEY>"
      CLOUDINARY_NAME="<your_CLOUDINARY_NAME>"
      JWT_SECRET="<type_any_text>"
      ADMIN_EMAIL="<your_choice_mail>"
      ADMIN_PASSWORD="<your_choice_password>"
      STRIPE_SECRET_KEY="<your_stripe_api_key>"
   .env in admin
      VITE_BACKEND_URL = "http://localhost:4000"
   ```
5. Start the development servers:
   ```bash
   cd frontend
   npm run dev
   ```
   ```bash
   cd backend
   npm run dev
   ```
   ```bash
   cd admin
   npm run start
   ```
6. Open `http://localhost:5174/` in your browser.
   ```bash
      No products must be showing - you need to add some from admin panel interface at port:5174
      **Some products with images and details are available at assets in frontend**

      Frontend users - at port: 5173

      you can change these port preference at the respective vite.config.js files
   ```

## Technologies Used
- **Frontend**: React, Redux, React Router
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: JWT
- **Payment**: Stripe, Razorpay
- **Image Uploads**: Cloudinary, Multer
- **Deployment**: Vercel

## Deployment
To deploy the project on Vercel:
1. Push the code to GitHub.
2. Connect the repository to Vercel.
3. Deploy both the frontend and backend separately.

## Visit My Deployed website
   https://forever-frontend-khaki-kappa.vercel.app/

## Thank You
   -Saksham Sawhney

