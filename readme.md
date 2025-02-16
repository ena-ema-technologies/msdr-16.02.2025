### Initial skill Assessment task for MERN stack Developer

Hello
Thank you for your interest to join our team. To evaluate your expertise we've designed a task where you'll building a modern eCommerce platform that showcases any kind of products (you prefer) in an engaging way, making it easy for customers to browse, purchase, and stay informed. The platform will feature a sleek design, seamless navigation, and secure payment options to ensure a smooth shopping experience. Please check further

## Tech Preference:

### Frontend:

- Use Next.js as framework.
- Use Tailwind CSS for styling UI.
- Use Redux Toolkit for state management to handle shopping cart, wishlist, user authentication

### Backend:

- Use Node.js with Express.js for the backend.
- Implement the backend in a modular pattern (e.g., separate Interface, model, services, controllers, routes, for better maintainability on each module).
- Use Mongoose as the ODM library to interact with MongoDB for database operations.

## Key Functionalities

### User Authentication

(i) Customer Account :

- Allow customer to create an account by providing their name, email and phone number.
- customer must log in before placing an order.

(ii) Admin Account :

- View all products.
- Add, update, or delete products.
- View all orders placed by customers.
- Update order statuses (e.g., "Confirmed," "Processing," "Shipped," "Delivered").

### Wishlist & Shopping Cart Management

- Allow customer to add/remove products from their shopping cart and wishlist .
- Use local storage to temporarily store the shopping cart and wishlist data.
- Once the user logs in, sync the local storage data with the database to persist the shopping cart and wishlist.

### Real-Time Stock Availability

- Implement real-time stock availability for each product.
- Automatically remove out-of-stock items from the shopping cart or wishlist.
- Display stock status (e.g., "In Stock," "Out of Stock") on the product page.

### Payment Gateway Integration

- Integrate Stripe as payment gateway so that customers can easily pay online when placing their order.
- Offer a Cash on Delivery (COD) option for customers who prefer not to make an immediate online payment.

### Multi-Currency Support

- Allow users to view prices in different currencies based on their location. Use a real-time currency conversion API
- Local customers: BDT
- International customers: USD

### Order Submission and Database Storage

- Populate the order data into the database using Mongoose .
- Include the following fields in the order:
- Customer details (name, email, shipping address).
- Product details (product name, quantity, price).
- Order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Payment method (e.g., "Online Payment" or "Cash on Delivery").
- Orders should be stored in a dedicated orders collection in MongoDB.

### Real-Time Order Status Updates

- Provide real-time updates on the order status (e.g., "Confirmed," "Processing," "Shipped," "Delivered").
- Use any email service (e.g., SendGrid , Mailgun , or NodeMailer ) to notify customers via email at each stage of the order process.

### Customer Profile

- Customer can see their order histories
- Manage profile

### Admin Panel

- Manage Products
- Manage Orders update status (e.g., "Confirmed," "Processing," "Shipped," "Delivered") .
- View Customers

## Submission :

Please submit your task by replying [ career@enaema.com ], submission deadline 11:59 PM, 22nd February 2025.

- Project deployment URL
- An admin credentials to check dashboard functionalities
- A customer credentials to check shopping cart functionalities
- GitHub repository (ensure that your code visibility is set to public for further assessment)

Please note: We have included some assets here to inspire you on how the user interface should look. While it is not mandatory to follow them, feel free to use them as a reference and create your own unique idea.
