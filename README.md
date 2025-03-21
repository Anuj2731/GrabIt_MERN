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
![Screenshot (55)](https://github.com/user-attachments/assets/456f753f-13b4-468a-81bf-66063be70d56)
![Screenshot (56)](https://github.com/user-attachments/assets/f25c5ba3-25dc-48cb-b6f7-08723001c1d9)
![Screenshot (58)](https://github.com/user-attachments/assets/27f3a909-dafd-42b2-970f-4b327b6c9543)
![Screenshot (71)](https://github.com/user-attachments/assets/63601915-ee23-4fd0-b5d8-a295a35f0a9e)
![Screenshot (57)](https://github.com/user-attachments/assets/8ab0d37c-ea1c-4e7e-8201-bd8368f1ba33)
![Screenshot (59)](https://github.com/user-attachments/assets/34c6e7ce-7fc9-4fcf-a9f7-d8efcb9d5efc)
![Screenshot (69)](https://github.com/user-attachments/assets/50d4534f-c3fe-430c-9fa0-e761a98355ca)

💡 **Contributions are welcome!** If you encounter any issues or have suggestions for improvements, feel free to create an issue or submit a pull request. 🚀
