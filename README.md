# challenge13-E-Commerce

## Description
This application is an e-commerce platform that allows users to browse and purchase products. It features product listings, categories, and tags to help users find what they are looking for.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/challenge13-E-Commerce.git
   ```
2. Navigate to the project directory:
   ```bash
   cd challenge13-E-Commerce
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage
To start the application, run the following command:
```bash
npm start
```
The application will be running on `http://localhost:3001`.

## API Endpoints
- **GET /api/products**: Retrieve all products.
- **GET /api/products/:id**: Retrieve a single product by ID.
- **POST /api/products**: Create a new product.
- **PUT /api/products/:id**: Update a product by ID.
- **DELETE /api/products/:id**: Delete a product by ID.

- **GET /api/categories**: Retrieve all categories.
- **GET /api/categories/:id**: Retrieve a single category by ID.
- **POST /api/categories**: Create a new category.
- **PUT /api/categories/:id**: Update a category by ID.
- **DELETE /api/categories/:id**: Delete a category by ID.

- **GET /api/tags**: Retrieve all tags.
- **GET /api/tags/:id**: Retrieve a single tag by ID.
- **POST /api/tags**: Create a new tag.
- **PUT /api/tags/:id**: Update a tag by ID.
- **DELETE /api/tags/:id**: Delete a tag by ID.

## Models
- **Product**: Represents a product in the store.
- **Category**: Represents a category of products.
- **Tag**: Represents tags that can be associated with products.
- **ProductTag**: Represents the relationship between products and tags.

## License
This project is licensed under the MIT License.
