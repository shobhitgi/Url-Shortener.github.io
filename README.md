URL Shortener MERN App
Description
The URL Shortener MERN App is a full-stack web application that converts long, complex URLs into short, easy-to-share links. Developed using the MERN stack (MongoDB, Express.js, React.js, Node.js), it offers features like custom short URLs, click tracking, link expiration, and user-friendly link management. This secure and responsive platform ensures a seamless experience for users on both desktop and mobile devices.

Features
URL Shortening: Quickly transform long URLs into concise, shareable links.
Custom Aliases: Create personalized short links for branding or easy recall.
Click Tracking: Monitor link usage with real-time analytics, including click counts.
Mobile Responsiveness: Optimized for seamless usage across all devices.
Tech Stack
Frontend
React.js: Interactive and dynamic user interface.
Bootstrap/Tailwind: Responsive and modern styling.
Backend
Node.js with Express.js: Handles server-side logic and APIs.
MongoDB: Stores original and short URLs, user data, and analytics.
Additional Tools
JWT Authentication: Secure login and user session management.
RESTful APIs: Efficient and scalable backend architecture.
Installation
Prerequisites
Node.js and npm installed on your system.
MongoDB setup locally or on a cloud platform like MongoDB Atlas.
Steps
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-shobhitgi/url-shortener-mern.git
cd url-shortener-mern
Install dependencies:

bash
Copy
Edit
npm install
cd client
npm install
cd ..
Configure environment variables:
Create a .env file in the root directory and include:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
BASE_URL=http://localhost:5000
Start the application:

Backend:
bash
Copy
Edit
npm run server
Frontend:
bash
Copy
Edit
npm run client
Access the app in your browser:

arduino
Copy
Edit
http://localhost:3000
API Endpoints
Base URL: /api/v1
Endpoint	Method	Description
/shorten	POST	Shorten a long URL.
/shorten/custom	POST	Create a custom short URL.
/:shortUrl	GET	Redirect to the original URL.
/analytics/:shortUrl	GET	Fetch analytics for a short URL.
Usage
Shorten a URL:
Input a long URL to generate a short link.

Custom Short URLs:
Use the custom alias option to create branded or memorable links.

View Analytics:
Track the number of clicks, referrers, and other data for each short link.

Screenshots
Home Page

Analytics Dashboard

Future Enhancements
QR code generation for each short URL.
Advanced analytics with geographic and device data.
User dashboard with search and filtering for link management.
License
This project is licensed under the MIT License.

Contact
Author: Shobhit Sinha
Email: shobhitsinha231@gmail.com

Feel free to reach out for questions, suggestions, or contributions!

Let me know if you need further customization or changes!







