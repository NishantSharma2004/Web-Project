Restaurant Web Application
This project is a simple, interactive Restaurant Web Application built using HTML, CSS, and JavaScript. It showcases a restaurant menu with an add-to-cart feature, a cart summary display, and a payment simulation using a modal form. The app also includes sections for customer testimonials and a contact form for inquiries, making it a comprehensive single-page application for a restaurant's digital presence.

Features
1. Responsive Navigation Bar
A simple navigation bar with links to different sections of the page, including Home, About, Menu, Testimonials, and Contact.
A cart icon with a counter to show the number of items added to the cart.
2. Food Menu Section
Displays various food items with images, descriptions, and prices.
Each food item has an Add to Cart button that adds the item to the shopping cart.
3. Shopping Cart
Items added to the cart are stored in an array, allowing the cart to keep track of items and prices.
A Cart Summary display showing the list of items and the total price.
A button to proceed to payment when items are in the cart.
4. Payment Modal
A modal window for payment, where the user can enter Card Number, Expiration Date, and CVV.
Input validation to ensure that the card number is 16 digits, expiration date is in MM/YY format, and CVV is a 3-digit number.
Simulated payment processing, displaying a success message upon completion.
5. Testimonials Section
A section displaying customer reviews with photos, names, and star ratings.
Provides social proof to encourage users to try the restaurant.
6. Contact Form
A simple contact form for customers to send inquiries.
Includes fields for name, email, and message.
Technologies Used
HTML: Structure of the webpage.
CSS: Styling, layout, and responsiveness.
JavaScript: Handling cart functionality, managing modals, and simulating payment processing.
Code Highlights
List Comprehension for Cart Updates: The cart feature uses JavaScript arrays to store items dynamically.
Validation for Payment: JavaScript functions validate the credit card information before processing.
Modular Code Structure: Functions like addToCart(), showCart(), processPayment(), and openModal() make the code easy to understand and maintain.
How to Run the Project
Clone this repository to your local machine.
Open the index.html file in a web browser.
Navigate through different sections using the menu and test the cart and payment functionalities.
Screenshots
Food Menu and Add to Cart

Cart Summary and Payment Modal

Future Enhancements
Back-end Integration: Connect the contact form and payment process to a back-end server for real payment processing and form handling.
Database Connection: Store menu items, customer reviews, and cart data in a database to enhance scalability.
Enhanced Security: Use HTTPS and encryption methods for handling sensitive payment information.
