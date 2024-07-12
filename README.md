# -rn-assignment7-11117173
Introduction
This application allows users to browse a list of products, view detailed information about each product, add products to their cart, and manage their cart. The app fetches product data from an external API and stores selected items locally for persistence. This README provides an overview of the design choices, data storage implementation, and instructions on running the app.

Features
HomeScreen: Displays a list of available products fetched from an external API.
ProductDetailScreen: Shows detailed information about a selected product.
CartScreen: Displays the items added to the cart.
Drawer Navigation: Allows easy navigation between screens using a swipe gesture or button.
Local Storage: Uses AsyncStorage to store selected items locally on the device.
Design Choices
Libraries and Frameworks
React Native: Chosen for its cross-platform capabilities and strong community support.
Axios: Used for fetching data from the external API due to its ease of use and robust error handling.
AsyncStorage: Selected for local storage to persist cart data, ensuring the user's cart is saved even when the app is closed.
UI/UX Design
HomeScreen: Displays products in a clean, scrollable list. Each product has an "Add to Cart" button and a "View Details" button.
ProductDetailScreen: Provides a detailed view of the product with an "Add to Cart" button.
CartScreen: Lists all items added to the cart with options to remove individual items.
Drawer Navigation: Ensures seamless navigation between HomeScreen, ProductDetailScreen, and CartScreen.
Data Storage
Fetching Data from API
The app fetches product data from an external API using the fetch method. This ensures up-to-date product information is displayed to the user.


Product Cart Application
Introduction
This application allows users to browse a list of products, view detailed information about each product, add products to their cart, and manage their cart. The app fetches product data from an external API and stores selected items locally for persistence. This README provides an overview of the design choices, data storage implementation, and instructions on running the app.

Features
HomeScreen: Displays a list of available products fetched from an external API.
ProductDetailScreen: Shows detailed information about a selected product.
CartScreen: Displays the items added to the cart.
Drawer Navigation: Allows easy navigation between screens using a swipe gesture or button.
Local Storage: Uses AsyncStorage to store selected items locally on the device.
Design Choices
Libraries and Frameworks
React Native: Chosen for its cross-platform capabilities and strong community support.
Axios: Used for fetching data from the external API due to its ease of use and robust error handling.
AsyncStorage: Selected for local storage to persist cart data, ensuring the user's cart is saved even when the app is closed.
UI/UX Design
HomeScreen: Displays products in a clean, scrollable list. Each product has an "Add to Cart" button and a "View Details" button.
ProductDetailScreen: Provides a detailed view of the product with an "Add to Cart" button.
CartScreen: Lists all items added to the cart with options to remove individual items.
Drawer Navigation: Ensures seamless navigation between HomeScreen, ProductDetailScreen, and CartScreen.
Data Storage
Fetching Data from API
The app fetches product data from an external API using the fetch method. This ensures up-to-date product information is displayed to the user.


Installation and Running the App
Prerequisites
Node.js
npm or yarn
React Native CLI

Installation
Clone the repository:
bash
Copy code

git clone https://github.com/asareprosper143/rn-assignment7-11117173/
cd Code7

Install dependencies:
bash
npm install
