Back-end
Description of the Back-end Architecture:
StudyNotion uses a monolithic architecture, with the backend built using Node.js and Express.js, and MongoDB as the primary database. Monolithic architecture refers to a design approach where all the modules of the application are combined into a single large program, with a single codebase, to enable better control, security, and performance.
Node.js is a popular JavaScript runtime that allows us to run JavaScript code outside of the browser. Express.js is a web application framework that simplifies the process of building web applications in Node.js. MongoDB is a popular NoSQL database that allows for flexible data storage and retrieval, making it a suitable choice for complex applications like StudyNotion.
Features and Functionalities of the Back-end:
The back end of StudyNotion provides a range of features and functionalities, including:
User authentication and authorization: Students and instructors can sign up and log in to the platform using their email addresses and password. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
Course management: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
Payment Integration: Students will purchase and enrol on courses by completing the checkout flow that is followed by Razorpay integration for payment handling.
Cloud-based media management: StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
Markdown formatting: Course content in document format is stored in Markdown format, which allows for easier display and rendering on the front end.
Frameworks, Libraries, and Tools used:
The back end of StudyNotion uses a range of frameworks, libraries, and tools to ensure its functionality and performance, including:
Node.js: Node.js is used as the primary framework for the back end.
MongoDB: MongoDB is used as the primary database, providing a flexible and scalable data storage solution.
Express.js: Express.js is used as a web application framework, providing a range of features and tools for building web applications.
JWT: JWT (JSON Web Tokens) are used for authentication and authorization, providing a secure and reliable way to manage user credentials.
