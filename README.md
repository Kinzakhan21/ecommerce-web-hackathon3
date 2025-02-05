

**E-Commerce Marketplace**

This project was completed as part of Hackathon 3 in the GIAIC program. The task was to develop the marketplace for an e-commerce website, integrating various functionalities like product listing, inventory updates, price updates, and shipment tracking using APIs. Payment integration and user authentication were not required for this task.

Table of Contents

Project Overview

Technologies Used

Features

Setup Instructions

APIs Integrated

Project Structure

Conclusion


**Project Overview**

This project involves the development of an e-commerce marketplace that allows users to browse products, view product details, and see real-time updates on product prices and availability. The backend APIs for product data fetching, inventory, and shipment tracking were integrated seamlessly into the marketplace. The project does not include payment processing or authentication features.

**Technologies Used**

HTML/CSS: For basic structure and styling of the website.

JavaScript: For marketplace functionality.

React: To create reusable components and maintain the state of the application.

Axios: For fetching data from APIs.

Tailwind CSS: For responsive, utility-first styling.

Headless CMS: For managing and delivering product data.

APIs: For dynamic product data fetching, inventory management, and shipment tracking.


**Features**

Product Listing: Displays a list of available products with images, names, and prices.

Product Details: Users can click on a product to view more detailed information.

Inventory Management: Products' availability status and quantities are updated in real-time.

Price Updates: Product prices are dynamically fetched and updated from the backend.

Shipment Tracking: Integration with shipment APIs to show real-time tracking information for each product.


**Setup Instructions**

**Prerequisites:**

1. Node.js installed (>= v14.0.0)


2. **Clone the repository:**

git clone https://github.com/Kinzakhan21/your-repository-link.git


3. **Navigate into the project directory:**

cd your-project-directory


4. Install dependencies:

npm install


5. Start the development server:

npm run dev


6. Open http://localhost:3000 in your browser to see the marketplace.



**APIs Integrated**

Product Data API: Fetches product details including names, prices, and images.

**Inventory API**: Fetches product availability and stock status.

**Shipment Tracking API**: Allows users to track the shipping status of products.


**Project Structure**

/your-project
  ├── /public
  ├── /src
      ├── /components
      ├── /pages
      ├── /utils
  ├── /styles
  ├── package.json
  └── README.md

/components: Contains reusable UI components.

/pages: Contains different pages of the marketplace, like Home, Product, etc.

/styles: Contains CSS files for styling.

/utils: Contains utility functions like API calls.


**Conclusion**

This project demonstrates the ability to integrate various frontend technologies with external APIs to create an interactive e-commerce marketplace. The marketplace provides real-time data updates and a seamless shopping experiences




