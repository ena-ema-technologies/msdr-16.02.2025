### Initial skill Assessment task for MERN stack Developer

Hello thank you for your interest to join our team. To evaluate your expertise we've designed a task where you'll building a modern, user-friendly eCommerce platform that showcases any kind of products (you prefer) in an engaging way, making it easy for customers to browse, purchase, and stay informed. The platform will feature a sleek design, seamless navigation, and secure payment options to ensure a smooth shopping experience. Please check further

# Tech Preference:

1. Frontend:

- Use Next.js as framework.
- Use Tailwind CSS for styling UI.
- Use Redux Toolkit for state management to handle shopping cart, wishlist, user authentication

2. Backend:

- Use Node.js with Express.js for the backend.
- Implement the backend in a modular pattern (e.g., separate Interface, model, services, controllers, routes, for better maintainability on each module).
- Use Mongoose as the ODM library to interact with MongoDB for database operations.

## Key Functionalities

1. User Authentication

(i) Customer Account :

- Allow users to create an account by providing their name and email.
- Users must log in before placing an order.

(ii) Admin Account :

- View all products.
- Add, update, or delete products.
- View all orders placed by customers.
- Update order statuses (e.g., "Confirmed," "Processing," "Shipped," "Delivered").

2. Wishlist & Shopping Cart Management

- Allow users to add/remove products from their shopping cart and wishlist .
- Use local storage to temporarily store the shopping cart and wishlist data.
- Once the user logs in, sync the local storage data with the database to persist the shopping cart and wishlist.

3. Real-Time Stock Availability

- Implement real-time stock availability for each product.
- Automatically remove out-of-stock items from the shopping cart or wishlist.
- Display stock status (e.g., "In Stock," "Out of Stock") on the product page.

4. Payment Gateway Integration

- Integrate Stripe as the payment gateway so that customers can easily pay online when placing their order.
- Offer a Cash on Delivery (COD) option for customers who prefer not to make an immediate online payment.

5. Order Submission and Database Storage

- Populate the order data into the database using Mongoose .
- Include the following fields in the order:
- Customer details (name, email, shipping address).
- Product details (product name, quantity, price).
- Order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Payment method (e.g., "Online Payment" or "Cash on Delivery").
- Orders should be stored in a dedicated orders collection in MongoDB.

6. Real-Time Order Status Updates

- Provide real-time updates on the order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Use any email service (e.g., SendGrid , Mailgun , or SMTP ) to notify customers via email at each stage of the order process.

7. Customer Profile

- Customer can see their order histories
- Manage profile

8. Admin Panel

- Manage Products
- Manage Orders update status (e.g., "Confirmed," "Processing," "Shipped," "Delivered") .
- View Customers

## Submission :

- Project deployment URL
- Admin credentials to check dashboard functionalities
- Customer credentials to check shopping cart functionalities
- GitHub repository (ensure that your code visibility is set to public for further assessment)

Thank you!

Please note: We didn't provide you with a specific design either frontEnd or backEnd to allow your creativity to shine. Feel free to to design as your own. You are also welcome to use your previous projects
