# E-Commerce Web Application

Welcome to the **E-Commerce Web Application**! This is a full-stack project that allows users to browse products, manage their shopping cart, and make secure payments using **Stripe**. Admins can manage products and view order history. The application is built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).

> **Important:** The app is deployed on **Render** and may take a few minutes to load when first accessed. Please be patient; it will appear after a brief wait.

---

## Features

### For Users:

- **Account Registration and Login:** Users can create an account and log in securely using **JSON Web Tokens (JWT)**.
- **Browse Products:** Users can view and filter products by category, price range, and more.
- **Shopping Cart:** Users can add, remove, or update items in their cart.
- **Secure Checkout with Stripe:** Payments are handled securely using **Stripe**.
- **Order History:** Users can track their past orders and their statuses.

### For Admins:

- **Admin Dashboard:** Admins can log in to a special dashboard to manage products.
- **Product Management:** Admins can add new products, edit existing ones, or delete products from the catalog.

---

## Technologies Used

- **Frontend:** React.js, Redux, Material-UI (MUI)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment Gateway:** Stripe
- **Authentication:** JSON Web Tokens (JWT)
- **Deployment:** Render

---

## Getting Started

### Prerequisites

To run the project locally, make sure you have:

- **Node.js** and **npm** installed.
- A **MongoDB** instance (you can use **MongoDB Atlas** for cloud-based MongoDB).

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Abhik8261/E-Commerce-Web-Application.git
   cd E-Commerce-Web-Application


2. **Install backend dependencies:**

   ```bash
   cd backend
   npm install
     
3. **Install frontend dependencies:**

   ```bash
   cd ../frontend
   npm install

4. **Set up environment variables:**
    Create a **.env** file in the **backend** folder and add the following:
   ```bash
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
Replace **your_mongo_connection_string**, **your_jwt_secret**, and **your_stripe_secret_key** with your actual values.

5. **Run the application:**
- Backend: In the backend folder, run:
   ```bash
   npm start
- Frontend: In the frontend folder, run:
`  ```bash
   npm start  `

  
## How Users Can Interact with the App
  
**Registering and Logging In**
- To register, visit the homepage and click Register. Once you’ve signed up, you can log in using your credentials.

**Browsing Products**
- Navigate the homepage to view products, and use the filters to find products by category, price range, and more.

**Adding Items to Your Cart**
- When you find a product you like, click Add to Cart. Your items will be saved in your cart, which you can access at any time to make adjustments.

**Checkout and Stripe Payment**
- Once you’re ready to check out, go to your cart and click Proceed to Checkout.

- You’ll be redirected to a secure Stripe payment page to enter your payment details. Stripe processes the payment securely.

- After payment, you’ll receive an order confirmation, and you can view your order history anytime.


## Deployment

The application is deployed on **Render** and can be accessed at [https://ecommercewebsite-8rix.onrender.com](https://ecommercewebsite-8rix.onrender.com). It may take a few minutes to load the first time due to server initialization, but after that, it should work smoothly.

---

## 🔐 Demo Admin Credentials

If you'd like to explore the admin features of the application, feel free to log in using the test admin account below:

- **Username / Email:** Abhik.tech8261@gmail.com  
- **Password:** password

> ⚠️ This is a test account. Please do not make any permanent or inappropriate changes.

---

## Admin Dashboard Features

### Accessing the Admin Dashboard

- **Log In as Admin:** Admin users can log in to access the dashboard. Use the demo admin credentials provided above to explore.
- **Managing Products:** Admins can add new products, edit existing ones, or delete products from the catalog.
- **User Management:** Admins also have the ability to promote users to admin or remove user accounts.





 




