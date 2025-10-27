🛍️ Product Catalog with Filters – MVP
📖 Overview

The Product Catalog with Filters is a web-based application designed to showcase products in a clean, user-friendly catalog interface.
It enables users to search, sort, and filter products dynamically based on multiple criteria such as category, subcategory, brand, price range, rating, and stock availability.

This MVP (Minimum Viable Product) demonstrates a functional and responsive front-end system that can later be connected to a real database or backend API. It focuses on usability, clarity, and scalability — making it suitable for e-commerce websites, business portfolios, or any online product display system.

🎯 Objectives

To create an interactive product catalog with multiple filtering options.

To enhance the user experience by providing fast, relevant search results.

To ensure a responsive and mobile-friendly layout that works seamlessly on all screen sizes.

To lay the foundation for future integration with dynamic product APIs or databases.

🚀 Key Features
🔎 Search and Filter

Search Bar – Instantly search for products by name or keyword.

Category Filter – Select a product category to refine results.

Subcategory Filter – Further narrow down items within each category.

Brand Filter – View products from specific brands.

Price Range Filter – Set minimum and maximum price values to fit your budget.

Rating Filter – Filter products based on star ratings (1–4+ stars).

Stock Filter – Option to view only “In Stock” products.

📊 Sorting Options

Sort products alphabetically by name.

Sort by price (Low → High or High → Low).

Sort by customer rating.

⚡ Additional Features

Clear All Filters Button – Resets every filter and shows the complete product list.

Dynamic Product Grid – Products are dynamically loaded into a clean grid layout.

Loading Spinner – Displays while products are being fetched or processed.

Responsive Design – Adapts to desktop, tablet, and mobile devices smoothly.

Font Awesome Icons – Enhances the visual appeal and user interaction.

🧩 Technology Stack
Component	Technology Used	Description
Frontend	HTML5	Page structure and layout
Styling	CSS3 / Flexbox / Grid	User interface and responsive design
Scripting	Vanilla JavaScript (ES6)	Handles filtering, sorting, and UI interactions
Icons	Font Awesome	Provides professional icons for UI elements
Version Control	Git & GitHub	Source code management and version control
🏗️ Project Structure
Product-Catalog/
│
├── index.html                # Main HTML file
│
├── css/
│   └── styles.css            # Contains all CSS styles
│
├── js/
│   └── app.js                # JavaScript for filters, sorting, and search logic
│
└── assets/                   # (Optional) Product images or JSON data

⚙️ How It Works

The index.html file defines the overall structure — header, sidebar filters, and product grid.

The filters sidebar contains dropdowns and input fields for category, brand, price, and rating.

The JavaScript (app.js) dynamically loads product data, applies selected filters, and updates the product grid in real time.

The CSS file ensures that the layout remains responsive and visually appealing across devices.

The Font Awesome library adds intuitive icons for better user experience.

💻 How to Run the Project

Download or Clone the Repository

git clone https://github.com/your-username/product-catalog.git


Open the Project Folder

cd product-catalog


Launch the Application

Simply open the file index.html in your web browser.

All scripts and styles will load automatically.

Interact with the Catalog

Use the search bar to find products by name.

Apply filters for price, brand, or category.

Sort products and clear filters anytime.

🧠 Learning Outcomes

Through this project, you will learn how to:

Design and structure a real-world front-end application.

Implement dynamic filters using JavaScript.

Work with DOM manipulation and event handling.

Organize code using a modular folder structure.

Build responsive layouts using CSS Grid and Flexbox.

🧾 Future Enhancements

Connect with a real backend API to fetch live product data.

Add a product details page with full information and images.

Include user authentication and admin dashboard for managing products.

Implement shopping cart and checkout features.

Add pagination for large product lists.

📸 Screenshots (Add in your README)

Homepage view

Filters sidebar view

Search in action

Product sorting example

Mobile responsive layout

