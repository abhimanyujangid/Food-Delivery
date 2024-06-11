# Food Delivery Website

This is a full-stack food delivery website built using the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User authentication (Sign Up, Login, Logout)
- Browse restaurants and their menus
- Add items to cart
- Place orders
- Admin dashboard to manage restaurants and orders

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **State Management:** Redux
- **Styling:** CSS / Styled Components

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later) or yarn (v1.22.x or later)
- MongoDB (local or cloud)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/abhimanyujangid/Food-Delivery.git
    cd Food-Delivery
    ```

2. Install dependencies for both frontend and backend:

    ```bash
    # For backend
    cd backend
    npm install
    ```

    # For frontend
    cd ../frontend
    npm install
    ```

### Environment Variables

Create a `.env` file in the `backend` directory and add the following environment variables:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

### Running the Application

1. Start the backend server:

    ```bash
    cd backend
   


2. Start the frontend development server:

    ```bash
    cd frontend
    npm run dev
   

### Directory Structure

    ```
    Food-Delivery/
    ├── backend/
    │   ├── config/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   ├── middleware/
    │   └── server.js
    ├── frontend/
    │   ├── public/
    │   ├── src/
    │   │   ├── components/
    │   │   ├──────── ExploreMenu/
    │   │   ├──────── Header/
    │   │   ├──────── NAvbar/
    │   │   ├── pages/
    │   │   ├──────── Home/
    │   │   ├──────── Cart/
    │   │   ├──────── PlaceOrder/
    │   │   └── App.js
    │   ├── index.html/
    │   ├── package.json/
    ├── README.md
    └── .gitignore
    ```

## Usage

- **User Registration & Login:** Users can sign up and log in to their accounts.
- **Browse Restaurants:** Users can view a list of restaurants and their menus.
- **Add to Cart:** Users can add items to their cart.
- **Place Order:** Users can place an order from the items in their cart.
- **Admin Dashboard:** Admins can manage restaurants and orders.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


## Contact

For any inquiries, please contact abhimanyujangid79@gamil.com

