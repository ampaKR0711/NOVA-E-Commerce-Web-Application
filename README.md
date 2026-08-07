# 🛍️ NOVA

### Modern E-Commerce Web Application

> A responsive and interactive e-commerce platform designed to simulate a complete online shopping experience — from discovering products and applying filters to managing a wishlist, shopping cart, checkout, order confirmation, and order history.

---

# 🌐 Project Overview

**NOVA** is a frontend-focused e-commerce web application developed as part of my web development project work.

The project was designed to demonstrate how a modern online shopping platform can combine product discovery, product interaction, wishlist management, shopping-cart functionality, checkout, payment selection, order confirmation, and order history into one unified application.

Rather than creating a simple product-listing webpage, NOVA focuses on implementing a complete customer shopping journey.

The application follows the overall workflow:

```text
                         NOVA
                          │
                          ▼
                  Product Discovery
                          │
              ┌───────────┴───────────┐
              │                       │
              ▼                       ▼
           Search                 Categories
              │                       │
              └───────────┬───────────┘
                          ▼
                    Product View
                          │
                 ┌────────┴────────┐
                 │                 │
                 ▼                 ▼
              Wishlist            Cart
                                   │
                                   ▼
                               Checkout
                                   │
                                   ▼
                           Payment Selection
                                   │
                                   ▼
                           Order Confirmation
                                   │
                                   ▼
                             Order History
🎯 Project Objective

The primary objective of NOVA was to develop a functional, responsive, and visually appealing e-commerce application while gaining practical experience in modern web development.

The project focuses on implementing a complete shopping workflow rather than only creating a static product catalogue.

The major objectives were:

Build a modern e-commerce storefront
Create an organized product catalogue
Implement product search
Implement product filtering
Implement product sorting
Provide product viewing functionality
Implement wishlist management
Implement shopping-cart functionality
Allow users to modify product quantities
Calculate cart totals dynamically
Include shipping calculations
Develop a checkout workflow
Provide multiple simulated payment options
Generate order confirmation
Maintain order history
Persist relevant application data using browser storage
Create a responsive and user-friendly interface
Demonstrate practical frontend development concepts

The project therefore combines UI design, application logic, state management, browser persistence, and e-commerce workflows into one application.

❗ Problem Statement

Modern e-commerce applications require more than simply displaying products on a webpage.

A useful shopping platform needs to support the complete customer journey.

Users should be able to:

Discover products
Search for products
Browse categories
Filter products according to their requirements
Sort products
View product information
Save products for later
Add products to a shopping cart
Modify product quantities
Remove products
Review their selected products
Calculate the purchase amount
Proceed through checkout
Select a payment method
Complete an order
Receive order confirmation
Review previous orders

A basic product-listing webpage cannot provide this complete experience.

Therefore, NOVA was designed as an integrated e-commerce application in which the different stages of the shopping journey are connected together.

💡 Our Solution

NOVA provides a complete frontend-based e-commerce workflow.

Instead of treating product browsing, wishlist, cart, checkout, and orders as separate pages, the application connects them into a continuous shopping experience.

The overall solution can be represented as:

DISCOVER
    ↓
SEARCH
    ↓
FILTER
    ↓
SORT
    ↓
VIEW PRODUCT
    ↓
WISHLIST / ADD TO CART
    ↓
MANAGE CART
    ↓
CHECKOUT
    ↓
PAYMENT SELECTION
    ↓
ORDER CONFIRMATION
    ↓
ORDER HISTORY

The application dynamically responds to user actions throughout this process.

For example:

Add Product
     ↓
Shopping Cart
     ↓
Quantity Update
     ↓
Updated Subtotal
     ↓
Shipping Calculation
     ↓
Final Total
     ↓
Checkout
     ↓
Payment Selection
     ↓
Order Confirmation
     ↓
Order History

This creates a more realistic representation of an online shopping platform.

🏗️ System Architecture

The overall NOVA application can be represented through the following architecture:

                         NOVA
                          │
              ┌───────────┴───────────┐
              │                       │
              ▼                       ▼
       Product Catalogue          Navigation
              │
       ┌──────┼──────┐
       │      │      │
       ▼      ▼      ▼
    Search  Filter  Sort
       │      │      │
       └──────┼──────┘
              ▼
        Product View
              │
       ┌──────┴──────┐
       │             │
       ▼             ▼
    Wishlist        Cart
                      │
              ┌───────┼───────┐
              │       │       │
              ▼       ▼       ▼
          Quantity  Shipping  Total
              │       │       │
              └───────┼───────┘
                      ▼
                  Checkout
                      │
                      ▼
              Payment Selection
                      │
                      ▼
              Order Confirmation
                      │
                      ▼
                Order History
✨ Core Features
🏠 1. E-Commerce Storefront

The NOVA storefront acts as the main entry point to the shopping experience.

It provides users with a structured environment where they can browse available products and begin their shopping journey.

The storefront includes:

Product cards
Product images
Product names
Product prices
Product ratings
Category information
Shopping actions
Navigation
Product-discovery controls

The interface is designed to make product discovery straightforward and visually organized.

📦 2. Product Catalogue

NOVA uses a structured product catalogue as the foundation of the application.

Products contain information required for the shopping experience, including:

Product name
Product image
Product price
Product category
Product rating
Product description
Sale information where applicable

The product catalogue is connected to other application features such as:

Product Catalogue
       │
 ┌─────┼─────┬─────────┐
 ▼     ▼     ▼         ▼
Search Filter Sort   Product View
       │
       ▼
 Wishlist / Cart
🔎 3. Product Search

NOVA provides product-search functionality to improve product discovery.

Instead of manually browsing the complete catalogue, users can enter a search query to find relevant products.

The process is:

User enters search query
          ↓
Application processes query
          ↓
Products are matched
          ↓
Relevant products displayed

This makes the catalogue easier to navigate, particularly as the number of products increases.

🏷️ 4. Product Filtering

The application allows users to narrow down the displayed products according to available product attributes.

Filtering can be used to make product discovery more efficient.

The filtering workflow is:

Complete Product Catalogue
          ↓
       Apply Filter
          ↓
    Reduced Product Set
          ↓
     Relevant Results

This allows users to focus on products matching their requirements.

↕️ 5. Product Sorting

NOVA also provides sorting functionality.

Sorting allows users to control the order in which products are displayed.

Search, filtering, and sorting work together:

             Product Catalogue
                    │
        ┌───────────┼───────────┐
        │           │           │
        ▼           ▼           ▼
      Search      Filter       Sort
        │           │           │
        └───────────┼───────────┘
                    ▼
             Product Results

This creates a more flexible product-discovery experience.

👁️ 6. Product View

Users can interact with products to view additional information before making a shopping decision.

The product-view experience provides a bridge between product discovery and shopping actions.

Product Discovery
       ↓
   Product View
       ↓
 ┌─────┴─────┐
 ▼           ▼
Wishlist    Cart
❤️ 7. Wishlist

NOVA includes wishlist functionality.

The wishlist allows users to save products they are interested in without immediately adding them to their shopping cart.

Users can:

Add products to the wishlist
View saved products
Remove products from the wishlist

The wishlist provides a separate space for products that may be considered for purchase later.

The workflow is:

Product
   ↓
Add to Wishlist
   ↓
Wishlist
   ↓
Review Saved Products
   ↓
Remove / Continue Shopping
🛒 8. Shopping Cart

The shopping cart is one of the central components of NOVA.

Users can add products to their cart and manage their selected items before proceeding to checkout.

The cart supports:

Adding products
Removing products
Increasing quantity
Decreasing quantity
Reviewing selected products
Calculating subtotal
Calculating shipping
Calculating final order total

The overall workflow is:

Product
   ↓
Add to Cart
   ↓
Cart Item
   ↓
Quantity Management
   ↓
Subtotal
   ↓
Shipping
   ↓
Final Total
➕➖ 9. Quantity Management

Users can modify the quantity of products directly within the shopping cart.

             Cart Item
                 │
          ┌──────┴──────┐
          ▼             ▼
      Increase       Decrease
      Quantity       Quantity
          │             │
          └──────┬──────┘
                 ▼
          Updated Cart
                 │
                 ▼
          Updated Total

The application dynamically updates the relevant cart information when quantities change.

💰 10. Dynamic Price Calculation

NOVA dynamically calculates the shopping amount based on the selected products and their quantities.

The basic calculation follows:

Product Price × Quantity
            ↓
       Item Subtotal
            ↓
     All Cart Items
            ↓
     Cart Subtotal
            ↓
      Shipping Cost
            ↓
      Final Total

This creates a more realistic shopping-cart experience.

🚚 11. Shipping Calculation

Shipping is incorporated into the checkout calculation.

The final purchase amount therefore accounts for both the selected products and shipping.

The simplified workflow is:

Product Subtotal
       +
Shipping Cost
       =
Final Order Total
💳 12. Checkout Workflow

NOVA provides a checkout process that connects the shopping cart to order completion.

The checkout workflow allows the user to review their purchase and proceed toward order confirmation.

Shopping Cart
      ↓
Checkout
      ↓
Order Information
      ↓
Order Summary
      ↓
Payment Selection
      ↓
Confirm Order

The checkout stage represents the final part of the customer's shopping journey before order completion.

💳 13. Payment Options

NOVA provides multiple simulated payment methods to demonstrate how payment selection can be integrated into an e-commerce checkout.

Available options include:

💳 Card Payment

A card-payment interface is provided as one of the checkout options.

📱 UPI

A UPI payment option represents a commonly used digital-payment workflow.

💵 Cash on Delivery

Cash on Delivery is provided as an alternative payment option.

⚠️ Payment Disclaimer

The payment functionality in NOVA is a frontend simulation.

The application does not process real financial transactions.

No actual banking transaction or real payment processing takes place.

The payment options are included to demonstrate the user interface and workflow of an e-commerce checkout system.

✅ 14. Order Confirmation

After completing the checkout workflow, NOVA provides an order-confirmation experience.

The order-confirmation stage represents the successful completion of the simulated purchase.

Shopping Cart
      ↓
Checkout
      ↓
Payment Selection
      ↓
Confirm Order
      ↓
Order Confirmation

This provides the customer with a clear completion point.

📦 15. Order History

NOVA includes order-history functionality.

Completed orders can be retained and reviewed within the application.

The workflow is:

Completed Order
      ↓
Order Information
      ↓
Order History
      ↓
Previous Purchase Review

This allows the application to represent a more complete customer account experience.

👤 16. Account Interface

The application also includes an account-oriented interface for accessing relevant shopping information.

The account structure provides a foundation for future features such as:

User authentication
Personal information
Saved addresses
User-specific orders
Personalized shopping
Account management
💾 17. Browser Data Persistence

NOVA uses browser-based LocalStorage for persistence of relevant application information.

This allows selected information to remain available even after refreshing the page.

The concept can be represented as:

User Interaction
       ↓
Application State
       ↓
LocalStorage
       ↓
Persisted Browser Data
       ↓
Page Refresh
       ↓
Data Restored

This is particularly useful for shopping-related information such as:

Cart state
Wishlist state
Order information
🎨 UI / UX Design

NOVA was developed with a focus on both functionality and visual presentation.

The interface aims to provide a clean and understandable shopping experience.

🎯 Visual Hierarchy

Important information is presented with clear visual hierarchy.

This includes:

Product names
Product prices
Ratings
Product information
Shopping actions
Cart information
Checkout information
🧩 Consistent Components

Repeated interface elements maintain a consistent visual structure.

Examples include:

Product cards
Buttons
Navigation
Filters
Cart items
Checkout sections
Order information

This helps maintain consistency throughout the application.

📱 Responsive Design

The application is designed to provide a usable experience across different screen sizes.

Desktop
   ↓
Laptop
   ↓
Tablet
   ↓
Mobile

The interface is structured to maintain usability and readability across different devices.

🛠️ Technology Stack
Frontend
React
JavaScript
HTML
CSS
Development Environment
Vite
Node.js
npm
Browser Storage
LocalStorage
Version Control
Git
GitHub
🧠 Technical Concepts Demonstrated

The project demonstrates practical frontend-development concepts.

1️⃣ Component-Based Development

The application interface is organized into reusable UI components.

This allows different areas of the application to remain logically separated and makes the project easier to maintain and expand.

2️⃣ Application State

The application responds dynamically to user interactions.

Examples include:

Adding products
Removing products
Changing quantities
Adding wishlist items
Removing wishlist items
Completing checkout
3️⃣ Conditional Rendering

Different interface states can be displayed according to the current application state.

For example:

Shopping Cart
     │
     ├── Empty Cart
     │
     └── Cart With Products

Similarly:

Wishlist
     │
     ├── Empty Wishlist
     │
     └── Wishlist With Products
4️⃣ Dynamic Calculations

The application dynamically calculates shopping-related values such as:

Product quantity
Subtotal
Shipping
Final order amount
5️⃣ Browser Persistence

LocalStorage is used to persist relevant application information within the browser.

This helps maintain selected data across page refreshes.

🔄 Complete Customer Journey

A typical customer journey through NOVA is:

1. Open NOVA
       ↓
2. Browse Storefront
       ↓
3. Search for Product
       ↓
4. Apply Filters
       ↓
5. Sort Products
       ↓
6. View Product
       ↓
7. Add Product to Wishlist or Cart
       ↓
8. Open Shopping Cart
       ↓
9. Increase / Decrease Quantity
       ↓
10. Review Subtotal
       ↓
11. Review Shipping
       ↓
12. Review Final Total
       ↓
13. Proceed to Checkout
       ↓
14. Select Payment Method
       ↓
15. Confirm Simulated Order
       ↓
16. View Order Confirmation
       ↓
17. Review Order History
🧪 Application Testing

The major application workflows can be tested manually.

🔎 Product Discovery Testing
Open Store
   ↓
Search Product
   ↓
Apply Filter
   ↓
Sort Products
   ↓
Open Product
❤️ Wishlist Testing
Open Product
   ↓
Add to Wishlist
   ↓
Open Wishlist
   ↓
Review Product
   ↓
Remove Product
🛒 Shopping Cart Testing
Open Product
   ↓
Add to Cart
   ↓
Open Cart
   ↓
Increase Quantity
   ↓
Decrease Quantity
   ↓
Remove Product
💳 Checkout Testing
Add Product
   ↓
Shopping Cart
   ↓
Checkout
   ↓
Select Payment Method
   ↓
Confirm Order
   ↓
Order Confirmation
📦 Order History Testing
Complete Order
      ↓
Open Order History
      ↓
Review Previous Order
🐞 Development & Debugging

The application was developed through an iterative process.

The development workflow involved:

Running the application locally
Testing user interactions
Checking application behavior
Testing product search
Testing product filtering
Testing product sorting
Testing wishlist functionality
Testing cart functionality
Testing quantity changes
Verifying cart calculations
Testing checkout
Testing payment selection
Testing order confirmation
Checking order history
Testing browser persistence
Refining the user interface

This iterative process helped connect individual features into a complete shopping workflow.

📂 Project Structure

The project follows a modern frontend application structure.

NOVA/
│
├── public/
│   └── Public assets
│
├── src/
│   ├── Components
│   ├── Pages / Views
│   ├── Data
│   ├── Assets
│   └── Application Logic
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── README.md
└── PROJECT_CHECKLIST.md
⚙️ How to Run the Project
Prerequisites

The following software should be installed:

Node.js
npm
Git
1️⃣ Open the Project Folder

Open Command Prompt or PowerShell and navigate to the NOVA project directory.

Example:

C:\Users\KIIT0001\Downloads\nova-ecommerce\nova-ecommerce
2️⃣ Install Dependencies

Run:

npm install
3️⃣ Start the Development Server

Run:

npm run dev

Vite will display the local development address in the terminal.

It will normally look similar to:

http://localhost:5173/

Open the address shown by Vite in your browser.

🌐 Application Access

The project can be run locally through the Vite development server.

Local Development
       ↓
npm run dev
       ↓
Vite Development Server
       ↓
Browser
       ↓
NOVA E-Commerce Application

The local file:///C:/.../index.html path can be used to view the static HTML file, but the recommended method for the React/Vite application is to run it through the Vite development server using npm run dev.

📸 Application Screenshots

Screenshots of the completed NOVA application can be added to this README.

🏠 Storefront

Add storefront screenshot here.

📦 Product Catalogue

Add product catalogue screenshot here.

🔎 Search & Filtering

Add search and filtering screenshot here.

❤️ Wishlist

Add wishlist screenshot here.

🛒 Shopping Cart

Add shopping cart screenshot here.

💳 Checkout

Add checkout screenshot here.

✅ Order Confirmation

Add order confirmation screenshot here.

📦 Order History

Add order history screenshot here.

📈 Project Outcome

NOVA demonstrates how multiple frontend concepts can be combined to create a complete digital shopping experience.

The application brings together:

Product Discovery
        +
Search
        +
Filtering
        +
Sorting
        +
Product Interaction
        +
Wishlist
        +
Shopping Cart
        +
Quantity Management
        +
Price Calculation
        +
Shipping
        +
Checkout
        +
Payment Selection
        +
Order Confirmation
        +
Order History
        +
Browser Persistence
        =
Complete Frontend E-Commerce Experience

The project provided practical experience in designing and implementing an interactive web application with multiple interconnected features.

💼 Business Perspective

Although NOVA is primarily a frontend application, its functionality represents several important components of a digital-commerce business process.

👥 Customer Experience

The application focuses on reducing friction during:

Product discovery
Product selection
Wishlist management
Cart management
Checkout
🛍️ Digital Commerce Workflow

The project demonstrates the basic digital-commerce lifecycle:

Product
   ↓
Customer Interest
   ↓
Wishlist / Cart
   ↓
Checkout
   ↓
Order
   ↓
Order History
📊 Future Analytics Potential

A production version of NOVA could generate useful business metrics such as:

Most viewed products
Most added products
Wishlist trends
Cart abandonment
Average order value
Popular categories
Purchase frequency
Product performance
Sales trends

These metrics could later be connected to a Business Intelligence dashboard.

🔮 Future Roadmap

The following features represent potential future improvements and are not presented as completed functionality.

Phase 1 — Backend Integration

🔮 REST API

🔮 Backend server

🔮 Database integration

🔮 Server-side product management

🔮 Server-side order management

Phase 2 — Authentication

🔮 User registration

🔮 Login

🔮 Secure authentication

🔮 User-specific wishlist

🔮 User-specific order history

Phase 3 — Real Payment Infrastructure

🔮 Secure payment gateway

🔮 Transaction processing

🔮 Payment verification

🔮 Payment-status tracking

Real payment processing is intentionally not part of the current implementation.

Phase 4 — E-Commerce Analytics

🔮 Sales dashboard

🔮 Product-performance analytics

🔮 Customer-behavior analysis

🔮 Cart-abandonment analysis

🔮 Revenue analytics

Phase 5 — Intelligent Commerce

🔮 Product recommendation system

🔮 Personalized product discovery

🔮 Customer segmentation

🔮 Sales forecasting

🔮 AI-powered shopping assistant

🏆 Innovation & Implementation Highlights

✔ Complete frontend e-commerce workflow

✔ Product catalogue

✔ Product search

✔ Product filtering

✔ Product sorting

✔ Product viewing

✔ Wishlist functionality

✔ Dynamic shopping cart

✔ Quantity management

✔ Dynamic price calculation

✔ Shipping calculation

✔ Simulated Card / UPI / COD checkout

✔ Order confirmation

✔ Order history

✔ Account interface

✔ LocalStorage persistence

✔ Responsive interface

✔ React-based application

✔ Vite development environment

✔ Git and GitHub version control

📚 What I Learned

Developing NOVA provided practical experience in several areas of modern web development.

🌐 Frontend Development

Understanding how a multi-feature web application can be structured and developed using React.

🎨 User Interface Design

Learning how to create interfaces that balance visual presentation with practical usability.

⚙️ Application State

Understanding how user interactions can modify application state and influence different parts of the application.

🛒 E-Commerce Logic

Implementing practical e-commerce concepts such as:

Product management
Wishlist
Cart management
Quantity handling
Price calculations
Shipping
Checkout
Orders
💾 Browser Storage

Understanding how LocalStorage can be used to persist application information on the client side.

🐞 Debugging

Testing application behavior, identifying issues, and refining functionality during development.

🔧 Development Tools

Practical experience with:

Node.js
npm
Vite
React
Git
GitHub
🌱 Development Journey

The development of NOVA progressed from a basic interface toward a more complete e-commerce application.

Basic UI
   ↓
Product Catalogue
   ↓
Search
   ↓
Filters
   ↓
Sorting
   ↓
Product Interaction
   ↓
Wishlist
   ↓
Shopping Cart
   ↓
Quantity Management
   ↓
Price Calculation
   ↓
Shipping
   ↓
Checkout
   ↓
Payment Selection
   ↓
Order Confirmation
   ↓
Order History
   ↓
Persistent Browser State
   ↓
Complete E-Commerce Experience

This progression helped develop a better understanding of how independent frontend features can be integrated into one application.

🎓 Project Relevance

NOVA demonstrates practical experience that can be relevant to roles involving:

Frontend Development
Web Development
Software Engineering
Business Applications
Product Development
UI/UX Implementation
Application Development

The project also demonstrates the ability to translate a real-world business workflow into an interactive software application.

👤 Author
Ampa Ranjan

B.Tech Computer Science & Engineering

Areas of Interest

📊 Data Analytics

⚙️ Data Engineering

📈 Business Intelligence

🌐 Web Development

🤖 Artificial Intelligence

💼 Enterprise Technology

📄 Project Purpose

NOVA was developed as an academic and learning project to gain practical experience in modern frontend web development and e-commerce application design.

The project is intended for:

✅ Academic Learning

✅ Skill Development

✅ Portfolio Demonstration

✅ Web Development Practice

⚠️ Disclaimer

NOVA is a student-developed frontend e-commerce project.

The application does not currently process real financial transactions.

Payment options are provided for demonstration of the checkout workflow only.

Product information used within the application is intended for demonstration purposes.

The project should not be considered a production-ready commercial e-commerce platform.

⭐ Final Note

NOVA demonstrates how individual frontend concepts can be combined to create a complete digital shopping experience.

From discovering products to completing a simulated purchase, the project brings together interface design, application logic, state management, browser persistence, and e-commerce workflows into one application.

              🛍️ NOVA

          DISCOVER
              ↓
           EXPLORE
              ↓
           SEARCH
              ↓
            FILTER
              ↓
             SORT
              ↓
           SELECT
              ↓
       WISHLIST / CART
              ↓
         MANAGE CART
              ↓
           CHECKOUT
              ↓
      PAYMENT SELECTION
              ↓
          CONFIRM
              ↓
       ORDER HISTORY
🛍️ NOVA — From Product Discovery to Digital Checkout.
