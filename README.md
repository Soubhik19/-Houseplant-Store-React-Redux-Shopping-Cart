# Houseplant Store – React & Redux Shopping Cart

## Project Overview
This is a React-based web application that simulates an online houseplant store. Users can browse products, add them to a shopping cart, and manage their selections. The project leverages **React**, **Redux Toolkit**, and **React Router** to create a dynamic, interactive, and modular application.

## Features

### Landing Page
- Background image with a welcoming design.
- Company name and a short description.
- "Get Started" button that navigates to the Product Listing page.

### Product Listing Page
- Displays **six unique houseplants** with thumbnails, names, and prices.
- Plants are grouped into at least three categories (e.g., Succulents, Ferns, Flowering).
- "Add to Cart" button for each plant:
  - Increments the shopping cart count.
  - Disables the button after adding.
  - Adds the plant to the cart state in Redux.

### Header
- Appears on both Product Listing and Shopping Cart pages.
- Includes a shopping cart icon showing the total number of items.
- Navigation links to switch between pages.

### Shopping Cart Page
- Displays all selected plants with thumbnails, names, and unit prices.
- Shows the **total number of plants** and **total cost**.
- Increment and decrement buttons to adjust quantities.
- Delete button to remove items from the cart.
- "Checkout" button shows a “Coming Soon” message.
- "Continue Shopping" button navigates back to the Product Listing page.

## Technologies Used
- **React** – for building the front-end components.
- **Redux Toolkit** – for managing global application state (shopping cart).
- **React Router** – for page navigation.
- **CSS / Tailwind (optional)** – for styling the application.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/houseplant-store.git
