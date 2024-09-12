# Product Management System

This is a simple product management system built using Flask, SQLite, and JavaScript (Axios). It allows you to manage categories and products, and dynamically filter and display products by category.

## Features
- Add and manage product categories
- Add and manage products associated with categories
- Filter products by category and display them dynamically

## Technologies Used
- **Backend**: Flask, SQLite, SQLAlchemy
- **Frontend**: HTML, CSS, JavaScript (Axios for making HTTP requests)
- **CORS**: Flask-CORS for cross-origin resource sharing

## Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd product-management-system
2. Create and activate a virtual environment (optional but recommended):


    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install the required dependencies:


    pip install -r requirements.txt
4. Create the SQLite database and initialize the app:


    python app.py
# Running the Application
1. Backend: Run the Flask application:


    python app.py
2.Frontend: Open index.html in your browser. You can use a local web server like Live Server (VSCode extension) or Python's built-in HTTP server:

    python -m http.server 5500
3. The backend will run on http://127.0.0.1:5000 and the frontend on http://127.0.0.1:5500.

# API Endpoints
## Categories:

GET /categories: Fetch all categories
POST /categories: Add a new category
PUT /categories/<id>: Update a category by ID
DELETE /categories/<id>: Delete a category by ID
## Products:

GET /products: Fetch all products
GET /products/category/<category_id>: Fetch products by category
POST /products: Add a new product
PUT /products/<id>: Update a product by ID
DELETE /products/<id>: Delete a product by ID

## Initial Data
On startup, the app will create some default categories and products:

Categories: Men's Clothing, Women's Clothing, Kids' Clothing
Products: Men's Casual Shirt, Women's Summer Dress, Kids' T-shirt, Men's Jeans, Women's Jacket
## Screenshots
Add New Category

Add New Product

Products Filtered by Category

# License
This project is licensed under the MIT License. See the LICENSE file for details.

    Once you've saved the above content in a `README.md` file, don't forget to replace `<your-repo-url>` with your repository URL, and add the necessary screenshots to your repository.
