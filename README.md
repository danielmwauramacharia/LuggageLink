**LuggageLink**
A Web-Based GIS Solution for Urban Luggage Storage and Management

![LuggageLink Interface]()

**Introduction**
LuggageLink is a web application designed to help travelers find, book, and pay for luggage storage locations within urban environments. Using a GIS-based system powered by Leaflet.js and OpenStreetMap, users can locate nearby storage facilities in real-time, compare prices, and securely book a spot. The platform offers a streamlined experience for tourists, business travelers, and event attendees.

**Deployed Site**: https://danielmwauramacharia.github.io/LuggageLink/
**Project Blog Article**: Final Project Blog
**Author LinkedIn**: Daniel Mwaura

**Prerequisites: Ensure you have the following software installed:**

Node.js (v14 or higher)
PostgreSQL (v12 or higher)
Git

**Steps to Set Up Locally**
git clone https://github.com/yourusername/luggagelink.git
cd luggagelink

**Install dependencies**:
Navigate to the project folder and run:
npm install

**Configure the database:**
Create a .env file in the root directory, and add your PostgreSQL connection string:
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=luggagelink
DB_HOST=localhost
DB_PORT=5432
Run database migrations: Set up the database tables:
npm run migrate

**Start the server:**
Run the application locally:
npm start

Access the application:
Open your browser and go to:
http://localhost:3000

**Usage**
Once the application is running:
Search for Luggage Storage: Use the interactive map to locate nearby luggage storage facilities.
Filter Results: Narrow down results based on availability, price, or user ratings.
Book and Pay: Select a facility, choose your storage duration, and securely pay using Stripe or PayPal.
Manage Bookings: View and manage your bookings in the user dashboard.
Provide Feedback: After your storage experience, leave a rating and review.

**Contributing**
We welcome contributions! To contribute:
Fork the repository.
Create a feature branch: git checkout -b feature-name.
Commit your changes: git commit -m "Add new feature".
Push to your branch: git push origin feature-name.
Submit a pull request.
Please follow our contribution guidelines before submitting a pull request.

**Related Projects**
Here are libraries related to LuggageLink that you might find helpful:

Leaflet.js – for interactive map integration.
OpenStreetMap – for open-source map data.

**Licensing**
This project is licensed under the MIT License. See the LICENSE file for details.
