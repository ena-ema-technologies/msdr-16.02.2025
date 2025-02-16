### Initial skill Assessment task for MERN stack Developer

Your task is building a modern, user-friendly eCommerce platform that showcases any kind of products in an engaging way, making it easy for customers to browse, purchase, and stay informed. The platform will feature a sleek design, seamless navigation, and secure payment options to ensure a smooth shopping experience

## Frontend:

- Use Tailwind CSS for styling to ensure a clean, responsive, and modern UI.
- Use Redux Toolkit for state management to handle shopping cart, wishlist, user authentication

## Backend:

- Use Node.js with Express.js for the backend.
- Implement the backend in a modular pattern (e.g., separate Interface, model, services, controllers, routes, for better maintainability on each module).
- Use Mongoose as the ODM library to interact with MongoDB for database operations.

## Key Features:

## Responsive Design

Ensure the application is fully responsive and works well on both desktop and mobile devices using Tailwind CSS .

## User Authentication

(i) Customer Account :

- Allow users to create an account by providing their name and email.
- Users must log in before placing an order.

(ii) Admin Account :
Create an admin account with credentials pre-defined in the database. Admins should be able to:

- View all products.
- Add, update, or delete products.
- View all orders placed by customers.
- Update order statuses (e.g., "Confirmed," "Processing," "Shipped," "Delivered").

## Wishlist & Shopping Cart Management

- Allow users to add/remove products from their shopping cart and wishlist .
- Use local storage to temporarily store the shopping cart and wishlist data.
- Once the user logs in, sync the local storage data with the database to persist the shopping cart and wishlist.

## Real-Time Stock Availability

- Implement real-time stock availability for each product.
- Automatically remove out-of-stock items from the shopping cart or wishlist.
- Display stock status (e.g., "In Stock," "Out of Stock") on the product page.

## Payment Gateway Integration

- Integrate Stripe as the payment gateway so that customers can easily pay online when placing their order.
- Offer a Cash on Delivery (COD) option for customers who prefer not to make an immediate online payment.

## Order Submission and Database Storage

- Populate the order data into the database using Mongoose .
- Include the following fields in the order:
- Customer details (name, email, shipping address).
- Product details (product name, quantity, price).
- Order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Payment method (e.g., "Online Payment" or "Cash on Delivery").
- Orders should be stored in a dedicated orders collection in MongoDB.

## Real-Time Order Status Updates

- Provide real-time updates on the order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Use any email service (e.g., SendGrid , Mailgun , or SMTP ) to notify customers via email at each stage of the order process.

## Admin Panel

- Create an admin panel where admins can:
- Manage Products
- Manage Orders update status (e.g., "Confirmed," "Processing," "Shipped," "Delivered") .
- View Customers

## Submission :

Please begin front-end development right away. The deadline for submission is August 25, 2024. We understand that you may not be able to complete everything to showcase your expertise, but we have assigned this task to assess your capabilities under pressure. Please provide the following information:

- Project deployment URL
- Admin credentials to check dashboard functionalities
- Customer credentials to check shopping cart functionalities
- GitHub repository (ensure that your code visibility is set to public for further assessment)

Thank you!

Please note: We didn't provide you with a specific design to allow your creativity to shine. Feel free to let your imagination run wild and come up with something unique!
