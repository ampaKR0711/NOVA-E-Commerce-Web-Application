# 🛍️ NOVA

### 🚀 Modern E-Commerce Web Application

**Product Discovery • Search • Filtering • Wishlist • Cart • Checkout • Order Management**

<p align="center">

🛒 **Discover** &nbsp; • &nbsp;
🔎 **Explore** &nbsp; • &nbsp;
❤️ **Save** &nbsp; • &nbsp;
💳 **Checkout** &nbsp; • &nbsp;
📦 **Manage Orders**

</p>

---

### 🧠 End-to-End Frontend E-Commerce Experience

> **NOVA** is a responsive and interactive e-commerce web application designed to simulate a complete digital shopping journey — from discovering and filtering products to managing a wishlist, shopping cart, checkout, simulated payment selection, order confirmation, and order history.

---

# 🌐 Project Overview

**NOVA** was developed as a practical frontend web-development project focused on transforming a basic product catalogue into a **complete interactive shopping experience**.

The application brings together product discovery, search, categories, filtering, sorting, wishlist management, cart operations, dynamic pricing, checkout, payment selection, order confirmation, and order history.

### 🛍️ Complete Shopping Journey

```text
                         🛍️ NOVA
                            │
                            ▼
                   PRODUCT DISCOVERY
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
          🔎 SEARCH     🗂️ CATEGORY    ⚙️ FILTER
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                         ↕️ SORT
                            │
                            ▼
                    🛍️ PRODUCT VIEW
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
             ❤️ WISHLIST            🛒 CART
                                       │
                                       ▼
                              QUANTITY MANAGEMENT
                                       │
                                       ▼
                                💰 PRICE CALCULATION
                                       │
                                       ▼
                                  🚚 CHECKOUT
                                       │
                                       ▼
                                💳 PAYMENT
                                       │
                                       ▼
                                ✅ CONFIRMATION
                                       │
                                       ▼
                                 📦 ORDER HISTORY
```

---

# 🎯 Project Objective

The primary objective was to develop a **functional, responsive, visually appealing, and interactive e-commerce application** using modern frontend technologies.

### The project focuses on:

| Area | Implementation |
|---|---|
| 🛍️ Product Discovery | Product catalogue and browsing |
| 🔎 Search | Product search functionality |
| 🗂️ Navigation | Category-based browsing |
| ⚙️ Filtering | Product refinement |
| ↕️ Sorting | Product organization |
| ❤️ Wishlist | Save products for later |
| 🛒 Cart | Manage selected products |
| 💰 Pricing | Dynamic order calculation |
| 🚚 Checkout | Structured purchase workflow |
| 💳 Payment | Simulated payment selection |
| 📦 Orders | Order confirmation & history |
| 💾 Persistence | Browser LocalStorage |
| 📱 UI | Responsive interface |

---

# ❗ Problem Statement

A basic product-listing website does not provide the complete experience expected from a modern e-commerce platform.

A user should be able to move seamlessly through:

```text
DISCOVER
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
MANAGE QUANTITY
   ↓
REVIEW PRICE
   ↓
CHECKOUT
   ↓
PAYMENT
   ↓
CONFIRM
   ↓
ORDER HISTORY
```

### 💡 The Challenge

The challenge was to connect these individual functionalities into **one coherent application**, where changes made by the user are reflected throughout the shopping workflow.

---

# 💡 Solution

NOVA provides a unified frontend shopping platform where users can:

```text
        🛍️ DISCOVER
             ↓
        🔎 EXPLORE
             ↓
      ⚙️ FILTER / SORT
             ↓
       🛒 SELECT ITEMS
             ↓
       ❤️ SAVE ITEMS
             ↓
       💰 REVIEW PRICE
             ↓
        🚚 CHECKOUT
             ↓
       💳 SELECT PAYMENT
             ↓
       ✅ CONFIRM ORDER
             ↓
       📦 VIEW HISTORY
```

The application combines **React components, application state, user interactions, browser persistence, and responsive UI design** to create the complete experience.

---

# ✨ Key Features

## 🔎 Product Discovery

NOVA provides an organized product catalogue designed to make product exploration simple and efficient.

### Features

- 🔍 Product search
- 🗂️ Category browsing
- 💰 Price filtering
- ⭐ Rating filtering
- ↕️ Product sorting
- 🛍️ Product selection

---

## ❤️ Wishlist

The wishlist allows users to save products for future consideration.

```text
🛍️ PRODUCT
     │
     ▼
❤️ ADD TO WISHLIST
     │
     ▼
❤️ SAVED PRODUCTS
     │
     ├───────────────┐
     ▼               ▼
REMOVE          CONTINUE
PRODUCT         SHOPPING
```

### Includes

✔ Add products  
✔ Remove products  
✔ View saved products  
✔ Persistent wishlist state  

---

## 🛒 Shopping Cart

The shopping cart acts as the central point for managing selected products.

### Cart Operations

```text
             🛒 CART
                │
      ┌─────────┼─────────┐
      ▼         ▼         ▼
     ➕        ➖         ❌
  Increase   Decrease   Remove
  Quantity   Quantity   Product
      │         │         │
      └─────────┼─────────┘
                ▼
          UPDATED CART
                │
                ▼
        💰 PRICE CALCULATION
```

Users can:

- Add products
- Increase quantity
- Decrease quantity
- Remove products
- Clear cart
- View item count
- Review selected products

---

## 💰 Dynamic Price Calculation

The order value is dynamically calculated according to the selected products and quantities.

```text
Product Price
      ×
Quantity
      ↓
Item Total
      ↓
Cart Subtotal
      +
Shipping
      ↓
💰 FINAL TOTAL
```

The displayed amount changes as users modify their cart.

---

## 🚚 Checkout

The checkout workflow connects cart management with order completion.

```text
🛒 CART
  ↓
🧾 ORDER REVIEW
  ↓
👤 CUSTOMER DETAILS
  ↓
🚚 SHIPPING DETAILS
  ↓
💳 PAYMENT SELECTION
  ↓
✅ CONFIRM ORDER
```

This creates a structured multi-step shopping workflow.

---

## 💳 Payment Selection

NOVA includes simulated payment-method selection.

| 💳 Method | 📌 Purpose |
|---|---|
| Credit / Debit Card | Simulated card payment |
| UPI | Simulated digital payment |
| Cash on Delivery | Simulated COD |

> ⚠️ **Payment processing is simulated for educational purposes. No real financial transaction is performed.**

---

## ✅ Order Confirmation

Once checkout is completed, the application provides an order-confirmation experience.

```text
CHECKOUT
   ↓
PAYMENT
   ↓
ORDER REVIEW
   ↓
CONFIRM
   ↓
🎉 ORDER CONFIRMED
```

---

## 📦 Order History

Completed orders can be retained and reviewed through the order-history functionality.

```text
🛍️ COMPLETED ORDER
          ↓
       💾 SAVE
          ↓
    📦 ORDER HISTORY
          ↓
     🔎 REVIEW
```

---

## 💾 LocalStorage Persistence

NOVA uses browser **LocalStorage** to preserve relevant application information.

```text
              USER ACTION
                  │
                  ▼
           APPLICATION STATE
                  │
                  ▼
            💾 LOCALSTORAGE
                  │
                  ▼
          BROWSER PERSISTENCE
                  │
                  ▼
              PAGE REFRESH
                  │
                  ▼
           STATE RESTORED
```

Relevant information includes:

- 🛒 Cart items
- ❤️ Wishlist items
- 📦 Order information

---

# 🎨 UI / UX Design

NOVA focuses not only on functionality but also on creating a **clean and engaging shopping interface**.

### Design Principles

**🎯 Clear Visual Hierarchy**

Important product and shopping information is presented in an organized manner.

**🧩 Consistent Components**

Product cards, buttons, navigation elements, cart sections, and checkout components follow a consistent structure.

**⚡ Interactive Experience**

User actions immediately affect relevant application elements.

**📱 Responsive Layout**

The interface is designed to remain usable across different screen sizes.

```text
🖥️ DESKTOP
     ↓
💻 LAPTOP
     ↓
📱 TABLET
     ↓
📱 MOBILE
```

---

# 🔄 End-to-End Application Workflow

```text
┌─────────────────────┐
│  🛍️ PRODUCT STORE   │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│ 🔎 SEARCH / FILTER  │
│    / SORT PRODUCTS  │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│ 🛍️ PRODUCT VIEW     │
└───────┬─────┬───────┘
        │     │
        ▼     ▼
   ❤️ WISHLIST  🛒 CART
                  │
                  ▼
        ┌─────────────────┐
        │ 💰 PRICE REVIEW │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ 🚚 CHECKOUT     │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ 💳 PAYMENT      │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ ✅ CONFIRMATION │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ 📦 ORDER HISTORY│
        └─────────────────┘
```

---

# 🏗️ Application Architecture

```text
                    🛍️ NOVA
                       │
                       ▼
                ⚛️ REACT FRONTEND
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
   PRODUCT DATA    APPLICATION      USER ACTIONS
                    STATE
        │              │              │
        └──────────────┼──────────────┘
                       ▼
               SHOPPING WORKFLOW
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
     ❤️ WISHLIST     🛒 CART      🚚 CHECKOUT
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                💾 LOCALSTORAGE
                       │
                       ▼
                📦 ORDER HISTORY
```

---

# 🛠️ Technology Stack

### 💻 Frontend

```text
⚛️ React
🟨 JavaScript
🌐 HTML
🎨 CSS
⚡ Vite
```

### 🎨 UI & Interaction

```text
🎬 Framer Motion
🔷 Lucide React
```

### 💾 Browser Storage

```text
💾 LocalStorage
```

### 🔧 Development

```text
🟢 Node.js
📦 npm
🔀 Git
🐙 GitHub
```

---

# 📂 Project Structure

```text
NOVA
│
├── 📁 public/
│
├── 📁 src/
│   ├── 📁 components/
│   ├── 📁 data/
│   ├── 📄 App.jsx
│   ├── 📄 main.jsx
│   └── ...
│
├── 📄 index.html
├── 📄 package.json
├── 📄 package-lock.json
├── 📄 vite.config.js
├── 📄 .gitignore
├── 📄 PROJECT_CHECKLIST.md
└── 📄 README.md
```

---

# ⚙️ How to Run

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Start the Development Server

```bash
npm run dev
```

### 3️⃣ Open the Application

Vite will provide a local development URL.

```text
http://localhost:5173/
```

Open the displayed URL in your browser to launch NOVA.

---

# 🧪 Testing & Validation

NOVA was tested across the primary shopping workflows.

### 🔬 Functional Testing

| Feature | Validation |
|---|---|
| 🛍️ Product Catalogue | ✔ |
| 🔎 Search | ✔ |
| 🗂️ Categories | ✔ |
| ⚙️ Filtering | ✔ |
| ↕️ Sorting | ✔ |
| ❤️ Wishlist | ✔ |
| 🛒 Cart | ✔ |
| ➕➖ Quantity | ✔ |
| 💰 Price Calculation | ✔ |
| 🚚 Checkout | ✔ |
| 💳 Payment Selection | ✔ |
| ✅ Order Confirmation | ✔ |
| 📦 Order History | ✔ |
| 💾 LocalStorage | ✔ |

### 🎨 Interface Testing

✔ Navigation  
✔ Product presentation  
✔ Button interactions  
✔ Cart behaviour  
✔ Wishlist behaviour  
✔ Checkout flow  
✔ Responsive layout  
✔ Overall UI consistency  

---

# 📈 Project Outcome

NOVA successfully demonstrates the development of a **complete interactive frontend e-commerce application**.

### 🛍️ Shopping Experience

**Product Discovery → Search → Filter → Sort → Product Selection**

### ❤️ Customer Interaction

**Wishlist → Cart → Quantity Management → Price Calculation**

### 🚚 Purchase Workflow

**Checkout → Payment Selection → Confirmation → Order History**

### 💾 Technical Implementation

**React → State Management → LocalStorage → Responsive UI**

---

# 📚 What I Learned

The development of NOVA provided practical experience in transforming individual frontend concepts into one integrated application.

### ⚛️ React Development

- Component-based architecture
- Interactive UI development
- Application state handling

### 🧠 Application Logic

- Managing changing state
- Connecting user actions to UI updates
- Synchronizing cart and wishlist behaviour

### 🛍️ E-Commerce Development

- Product discovery
- Search
- Filtering
- Sorting
- Wishlist functionality
- Cart management
- Checkout workflows
- Order management

### 💾 Browser Persistence

- LocalStorage
- Persistent application state
- Restoring information after refresh

### 🎨 UI / UX

- Visual hierarchy
- Responsive layouts
- Interactive components
- User-oriented navigation

### 🔧 Development Workflow

- Vite development environment
- npm dependency management
- Frontend debugging
- Git version control
- GitHub repository management

---

# 🏆 Key Highlights

```text
                 🛍️ NOVA
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
   🔎 DISCOVER    ❤️ SAVE      🛒 CART
       │            │            │
       └────────────┼────────────┘
                    ▼
              💰 CALCULATE
                    │
                    ▼
               🚚 CHECKOUT
                    │
                    ▼
                💳 PAYMENT
                    │
                    ▼
               ✅ CONFIRM
                    │
                    ▼
             📦 ORDER HISTORY
```

### ⭐ Project Highlights

✔ Complete frontend shopping journey  
✔ Search, filtering and sorting  
✔ Wishlist management  
✔ Dynamic shopping cart  
✔ Quantity management  
✔ Dynamic price calculation  
✔ Checkout workflow  
✔ Simulated payment selection  
✔ Order confirmation  
✔ Order history  
✔ LocalStorage persistence  
✔ Responsive UI  
✔ React component architecture  
✔ Git & GitHub workflow  

---

# 🎓 Project Relevance

NOVA demonstrates practical skills in:

### **Frontend Development**

`React` • `JavaScript` • `HTML` • `CSS`

### **Application Development**

`State Management` • `LocalStorage` • `Component Architecture`

### **UI / UX**

`Responsive Design` • `Interactive Interfaces` • `User Experience`

### **Development Tools**

`Vite` • `npm` • `Git` • `GitHub`

The project also creates a foundation for future integration with:

**Backend APIs • Databases • Authentication • Payment Gateways • Analytics • AI Recommendations**

---

# 🔮 Future Roadmap

## 🚀 Phase 1 — Current Application

```text
✔ Product Catalogue
✔ Search
✔ Categories
✔ Filtering
✔ Sorting
✔ Wishlist
✔ Shopping Cart
✔ Checkout
✔ Simulated Payment
✔ Order Confirmation
✔ Order History
✔ LocalStorage
```

## ⚙️ Phase 2 — Backend Integration

```text
Node.js / Express
        ↓
REST APIs
        ↓
Database
        ↓
User Authentication
        ↓
Server-Side Orders
```

Potential additions:

- User accounts
- Login and registration
- Database-backed products
- Server-side orders
- Customer profiles

## 🏪 Phase 3 — Advanced E-Commerce

- Admin dashboard
- Inventory management
- Product reviews
- Coupons and discounts
- Order tracking
- Customer accounts
- Real payment gateway integration

## 🤖 Phase 4 — Intelligent Commerce

```text
Customer Behaviour
        ↓
      Analytics
        ↓
   Recommendation
      Engine
        ↓
Personalized Shopping
```

Potential additions:

- AI product recommendations
- Personalized shopping
- Customer behaviour analytics
- Sales analytics
- Demand prediction
- Business intelligence dashboards

---

# 📊 Future System Vision

```text
                         🛍️ NOVA
                            │
                            ▼
                    ⚛️ FRONTEND
                            │
                            ▼
                     🔗 BACKEND API
                            │
          ┌─────────────────┼─────────────────┐
          ▼                 ▼                 ▼
       👤 USERS          🛍️ PRODUCTS       📦 ORDERS
          │                 │                 │
          └─────────────────┼─────────────────┘
                            ▼
                       🗄️ DATABASE
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
          💳 PAYMENTS    📊 ANALYTICS   🤖 AI
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                  🚀 INTELLIGENT COMMERCE
```

---

# 👤 Author

### **Ampa Ranjan**

🎓 **B.Tech — Computer Science & Engineering**  
🏫 **KIIT University**

### 💡 Areas of Interest

`Data Analytics` • `Business Intelligence` • `Power BI` • `Data Engineering` • `Web Development` • `AI & Analytics`

---

# ⚠️ Disclaimer

NOVA is an **educational and internship project** developed to demonstrate practical frontend web-development concepts.

The payment functionality is **simulated** and does not process real financial transactions.

No real customer payments or financial information are processed by the application.

---

# ⭐ Final Note

```text
╔══════════════════════════════════════════════╗
║                  🛍️ NOVA                    ║
║                                              ║
║        FROM PRODUCT DISCOVERY                ║
║                  ↓                           ║
║            TO DIGITAL CHECKOUT               ║
║                  ↓                           ║
║        TO COMPLETE ORDER MANAGEMENT          ║
╚══════════════════════════════════════════════╝
```

**NOVA demonstrates how modern frontend technologies, interactive application logic, state management, browser persistence, responsive design, and user-centric thinking can be combined to create a complete digital shopping experience.**

### 🛍️ NOVA — **Discover. Explore. Shop. Experience.**
