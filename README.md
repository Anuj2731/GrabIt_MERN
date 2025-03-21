# 🛒 Grab It - MERN Stack E-Commerce Website

This is a fully functional e-commerce website built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. The platform allows users to browse products, add them to the cart, manage addresses, place orders, and make payments using Stripe.

## 🌟 Features

- 🔐 **User Authentication** - Register, login, email verification, and password reset.
- 🛍 **Product Management** - View products, categories, and subcategories.
- 🛒 **Shopping Cart** - Add, remove, and update cart items.
- 🚚 **Address Management** - Save and manage multiple shipping addresses.
- 💳 **Secure Payments** - Integrated with **Stripe** for smooth transactions.
- 📦 **Order Tracking** - Users can track their order history.
- 📡 **Cloud Image Upload** - Upload product images using Cloudinary.
- 🛠 **Admin Panel (Optional)** - Manage users, products, and orders.

## 🚀 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **Payment Gateway**: Stripe
- **Image Hosting**: Cloudinary

## 📦 Installation

1️⃣ **Clone the repository**:  
```sh
git clone https://github.com/your-username/Grab-It.git
cd Grab-It
```

2️⃣ **Install dependencies**:  
- Backend:  
```sh
cd server
npm install
```
- Frontend:  
```sh
cd client
npm install
```

3️⃣ **Set up environment variables**:  
Create a `.env` file in the **server** folder and add the necessary **MongoDB, Stripe, and Cloudinary keys**.

4️⃣ **Run the backend**:  
```sh
cd server
npm run dev
```

5️⃣ **Run the frontend**:  
```sh
cd client
npm run dev
```

## 💳 Payment Testing

To test the payment functionality, use the following **Stripe test card**:  
- **Card Number**: `4242 4242 4242 4242`  
- **Expiry**: Any future date  
- **CVC**: Any 3-digit number  

⚠️ This is a **test card** provided by Stripe and does not process real payments.

## 🎯 Future Enhancements

✅ **Implement Wishlist Feature**  
✅ **Add Reviews & Ratings for Products**  
✅ **Introduce Admin Panel for Better Management**  

### 🚀 **Live Demo:** *https://grabit-sand.vercel.app*  
💡 **Contributions are welcome!** If you encounter any issues or have suggestions for improvements, feel free to create an issue or submit a pull request. 🚀
