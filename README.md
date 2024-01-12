**Description of the Back-end Architecture:**
- **Monolithic Architecture:** StudyNotion employs a monolithic architecture for enhanced control, security, and performance. This approach combines all application modules into a single large program with a unified codebase.
- **Technologies Used:**
  - **Node.js and Express.js:** The backend is built using Node.js, a JavaScript runtime enabling code execution outside the browser, and Express.js, a web application framework simplifying Node.js web app development.
  - **MongoDB:** Serving as the primary database, MongoDB, a popular NoSQL database, is utilized for flexible data storage and retrieval, ideal for StudyNotion's complex requirements.

**Features and Functionalities of the Back-end:**
- **User Authentication and Authorization:**
  - Students and instructors can sign up and log in using email and password.
  - Supports OTP (One-Time Password) verification and forgot password functionality.
- **Course Management:**
  - Instructors can CRUD (create, read, update, delete) courses, manage content, and media.
  - Students can view and rate courses.
- **Payment Integration:**
  - Checkout flow for course purchase with Razorpay integration for secure payment handling.
- **Cloud-Based Media Management:**
  - Utilizes Cloudinary, a cloud-based media management service, for storing and managing images, videos, and documents.
- **Markdown Formatting:**
  - Stores course content in Markdown format for seamless display and rendering on the front end.

**Frameworks, Libraries, and Tools Used:**
- **Node.js:**
  - Primary framework ensuring the functionality of the back end.
- **MongoDB:**
  - Primary database offering flexible and scalable data storage.
- **Express.js:**
  - Web application framework providing essential features and tools for web app development.
- **JWT (JSON Web Tokens):**
  - Utilized for authentication and authorization, ensuring secure management of user credentials.
