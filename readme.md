### Initial skill Assessment task for MERN stack Developer

Your task is building a modern, user-friendly eCommerce platform that showcases any kind of products in an engaging way, making it easy for customers to browse, purchase, and stay informed. The platform will feature a sleek design, seamless navigation, and secure payment options to ensure a smooth shopping experience

## Frontend:

- Use Tailwind CSS for styling to ensure a clean, responsive, and modern UI.
- Use Redux Toolkit for state management to handle shopping cart, wishlist, user authentication

## Backend:

- Use Node.js with Express.js for the backend.
- Implement the backend in a modular pattern (e.g., separate Interface, model, services, controllers, routes, for better maintainability).
- Use Mongoose as the ODM library to interact with MongoDB for database operations.

## Key Features:

1. Responsive Design
   Ensure the application is fully responsive and works well on both desktop and mobile devices using Tailwind CSS .

2. User Authentication
   (i) Customer Account :

- Allow users to create an account by providing their name and email.
- Users must log in before placing an order.

(ii) Admin Account :
Create an admin account with credentials pre-defined in the database. Admins should be able to:

- View all products.
- Add, update, or delete products.
- View all orders placed by customers.
- Update order statuses (e.g., "Confirmed," "Processing," "Shipped," "Delivered").

3. Wishlist & Shopping Cart Management

- Allow users to add/remove products from their shopping cart and wishlist .
- Use local storage to temporarily store the shopping cart and wishlist data.
- Once the user logs in, sync the local storage data with the database to persist the shopping cart and wishlist.

4. Real-Time Stock Availability

- Implement real-time stock availability for each product.
- Automatically remove out-of-stock items from the shopping cart or wishlist.
- Display stock status (e.g., "In Stock," "Out of Stock") on the product page.

5. Multi-Currency Support

- Allow users to view prices in different currencies based on their location. Use a real-time currency conversion API .
- Local customers: BDT
- International customers: USD

6. Payment Gateway Integration

- Integrate Stripe as the payment gateway so that customers can easily pay online when placing their order.
- Offer a Cash on Delivery (COD) option for customers who prefer not to make an immediate online payment.

7. Order Submission and Database Storage

- When a customer submits an order:
- Populate the order data into the database using Mongoose .
- Include the following fields in the order:
- Customer details (name, email, shipping address).
- Product details (product name, quantity, price).
- Order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Payment method (e.g., "Online Payment" or "Cash on Delivery").
- Orders should be stored in a dedicated orders collection in MongoDB.

8. Real-Time Order Status Updates

- Provide real-time updates on the order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Use any email service (e.g., SendGrid , Mailgun , or SMTP ) to notify customers via email at each stage of the order process.
- When the order is delivered:
- Add a 5% cashback of the total order value to the customer's account.
- Display the cashback amount in a dedicated section of the customer's account dashboard.
- Allow customers to use the cashback amount on their next purchase. The cashback will be automatically deducted from the total cost of their next order.

9. Admin Panel

- Create an admin panel where admins can:
- Manage Products :
- Add new products with details like name, price, stock quantity, and images.
- Update existing product details.
- Delete products.
- Manage Orders :
- View all orders placed by customers.
- Update the status of orders (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- View Customers :
- View a list of registered customers and their details.

## Submission :

Please begin front-end development right away. The deadline for submission is August 25, 2024. We understand that you may not be able to complete everything to showcase your expertise, but we have assigned this task to assess your capabilities under pressure. Please provide the following information:

- Project deployment URL
- Admin access to check functionalities
- GitHub repository (ensure that your code visibility is set to public for further assessment)

Thank you!

Please note: We didn't provide you with a specific design to allow your creativity to shine. Feel free to let your imagination run wild and come up with something unique!
