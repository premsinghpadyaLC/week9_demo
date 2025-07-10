

### Hello, I’m Premsingh Padya (Premsingh Padya, Karthika, Khusbhu (Webgate Team)) – Demostrating being Owner of New Footwear & Rice Merchants

Welcome to a walkthrough of how our **interactive e-commerce website** works, built using the **MVC (Model-View-Controller) architecture** to simulate real-world online shopping and admin management — **from both a customer’s and my admin perspective**.

Let me explain each part as if I’m showing you the actual functionality of the store — and how this digital system supports our physical business operations.

---

###  Home Page – First Impression

When a customer lands on the home page, they are greeted with a clean and welcoming interface.

* They see two major categories we deal in: **Footwear** and **Rice**.
* Each button allows the customer to start exploring products under that category.

**Behind the scenes:**
The *View* handles the display, the *Controller* manages the click event, and the *Model* prepares the product data.

---

###  Products Page – Browsing Options

Once a category is clicked, say **Footwear**, the customer sees a grid of products like:

* *Bata Running Shoes*
* *Adidas Sneakers*

Each product has:

* A price tag
* A “View Details” button
* An “Add to Cart” button

**As a store owner**, I love how easy this makes it for my customers to explore and make quick decisions.

**Behind the scenes:**

* The *Controller* takes the user input (category),
* The *Model* fetches filtered products,
* And the *View* renders them beautifully.

---

###  Product Detail Page – Closer Look

When a user clicks on "View Details," they’re taken to a **dedicated product page**.

It includes:

* Full description
* Category info
* Price
* And an “Add to Cart” button

This page helps build customer confidence by showing that we’re transparent and informative.

---

###  Cart Page – Shopping Cart System

When the customer adds products to the cart:

* They can **see a summary of what they selected**
* Adjust quantities
* Remove items if needed
* And see the **live total price**

From a business point of view, this improves customer trust and helps **reduce cart abandonment**.

---

###  Checkout – Final Step

When ready, customers can go to the **Checkout Page**, fill out:

* Name
* Address
* Payment Method (Credit Card / PayPal)

Once submitted, they see a **confirmation message** summarizing their purchase.
This page simulates order processing and shipping — essential parts of running a modern online business.

---

###  Login/Register Page – Customer Access

We’ve added a simple login system.

* For now, users can log in using hardcoded credentials like `admin / admin123`.
* In future, this will evolve into a full database-authenticated login system for customers and staff.

---

###  Admin Panel – My Control Room

As **the store owner**, I can log in and manage the inventory.

In the **Admin Panel**, I can:

* Add new products (name, category, price)
* View all current products
* Monitor activity (mock version for now)

No database? No problem. It works dynamically in memory, meaning I can **demo it anywhere** without a backend.

---

##  Why This System Matters

This system is more than a demo. It shows how **our store — a traditional Footwear and Rice merchant — can go digital**:

* Offer **modern customer experience**.
* Maintain **clean inventory management**.
* Keep the **interface mobile-friendly and accessible**.
* Ensure **admin-level control and updates** in real-time.

---

##  Technical Foundation (in short)

* **Model**: Manages data — products, cart, users.
* **View**: Displays pages — home, product lists, cart, etc.
* **Controller**: Connects actions to logic — like button clicks or form submissions.

---

##  Final Thoughts from Me (Premsingh Padya, Karthika, Khusbhu)

As a business owner stepping into the digital space, this project reflects:

* My commitment to innovation,
* My understanding of modern user behavior,
* And how I want to bring local businesses like ours into the online world without losing the human touch.

I thank my team Webgate and everyone who helped build and test this solution. We’re just getting started.

---
