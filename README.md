1. Dual Login System (Customer and Owner)
Explanation: The application has two separate login roles:
Owner: Manages menu details and operations.
Customer: Views menus and provides reviews.
Implementation: Role-based authentication using JWT ensures secure access control for owners and customers.

2. Additional Features 
Filtering and Sorting: Customers can filter menus by price, location, or cuisine.

3. Owner Dashboard for Adding Menu Details
Explanation:
Owners can add or update the menu for the day, including food items, descriptions, and prices.
The dashboard is user-friendly and only accessible to authenticated owners.
Implementation:
Backend API endpoints for adding/updating menus.
Data stored in a MongoDB collection for efficient retrieval.

4. Real-Time Display of Menus with Locations for Customers
Explanation:
Customers can view the menu details added by owners, along with the mess's location.
Location integration helps customers find nearby messes quickly.
Implementation:
Frontend uses React for displaying the menu.
Google Maps API (or similar) shows mess locations on a map interface.

5. Customer Review System for Menus
Explanation:
Customers can leave feedback or ratings for a specific menu.
Reviews help other customers make informed decisions and provide valuable feedback to owners.
Implementation:
Backend API for submitting and fetching reviews.
MongoDB stores reviews associated with specific menus and users.

6. Seamless Frontend Experience
Explanation:
React ensures dynamic and responsive UI/UX for both customers and owners.
State management using libraries like Redux or Context API for smooth data handling.

7. Secure Backend API
Explanation:
Built with Express.js, the backend provides robust endpoints for authentication, menu management, and reviews.
Middleware like cors ensures security and cross-origin compatibility.

8. Database Design (MongoDB)
Explanation:
Separate collections for users, menus, reviews, and mess locations.
Optimized schema design to handle relational data efficiently using embedded documents or references.

9. Hosting and Deployment
Explanation:
Frontend: Deployed on Netlify for fast and reliable performance.
Backend: Deployed on Render with proper API configurations, including CORS and environment variables.

10. Technology Stack Used
Frontend: React.js (with libraries like Axios for API calls).
Backend: Node.js and Express.js for building scalable APIs.
Database: MongoDB for storing data.
Authentication: JWT for secure and role-based access.
