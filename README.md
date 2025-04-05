# Aventura: Ultimate Hub for Thrill Seekers and Adventurers

## Project Overview

The "Aventura" project provides a comprehensive platform for adventure enthusiasts, offering a wide range of features to enhance their adventure planning, booking, and community engagement experiences. From detailed adventure listings and user reviews to itinerary planning and safety support, the platform caters to all aspects of adventure travel, ensuring users have a memorable and fulfilling experience.

## Key Features

### User Profiles
- **Registration and Authentication**: Secure account creation and login system
- **Profile Customization**: Personalization with profile pictures, bios, and favorite destinations

### Adventure Listings
- **Adventure Database**: Comprehensive collection of adventure activities and destinations
- **Filter and Search**: Advanced filtering by difficulty level, duration, location, and activity type
- **Detailed Listings**: In-depth information with high-quality photos, interactive maps, weather forecasts, difficulty ratings, and user reviews

### Reviews and Ratings
- **User Reviews**: Detailed reviews and ratings to share experiences
- **Rating System**: Overall ratings based on user reviews
- **Comment and Reply**: Community discussion on reviews

### Booking and Reservations
- **Online Booking**: Direct booking of guided tours and activities
- **Availability Calendar**: Real-time availability of slots
- **Payment Integration**: Secure payment gateways for transactions

### Blogs and Community Features
- **Expert Tips**: Articles and advice from adventure experts
- **Eco-Friendly Tips**: Guidelines for sustainable travel
- **Forums**: Space for discussions, tips, and advice

### Essentials Store
- **Product Management**: Browse products with filtering options
- **Product Listings**: Detailed information for each item
- **Order Processing**: Shopping cart and secure checkout with Stripe

## Tech Stack

- **Frontend**: React, Redux, TypeScript, SASS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Maps**: Mapbox API
- **Weather**: OpenWeather API
- **Payments**: Stripe API
- **Email**: EmailJS
- **Data Visualization**: Recharts

## Application Flow

The website has a simple navigation structure:
- **Homepage** leads to three main sections:
  - **Packages**: Browse and book adventure tours
  - **Shop**: Purchase essential adventure gear
  - **Blogs**: Read expert content and community posts

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/BhavaniDevulapalli1509/Aventura.git
   ```

2. Install dependencies:
   ```
   # Install backend dependencies
   npm install
   
   # Install frontend dependencies
   npm install
   ```

3. Configure environment variables:
   - Create `.env` file in the server directory
   - Add your API keys for Mapbox, OpenWeather, Stripe, etc.

4. Start the application:
   ```
   # Start backend 
   npm start
   
   # Start frontend 
   npm run dev
   ```

5. Access the application at `http://localhost:3000`

## REST API Resources

### Users
- `GET /users`: List all users
- `POST /users`: Create a new user
- `GET /users/{userId}`: Get specific user
- `PUT /users/{userId}`: Update user
- `DELETE /users/{userId}`: Delete user

### Adventure Packages
- `GET /packages`: List all packages
- `POST /packages`: Create a new package
- `GET /packages/{packageId}`: Get specific package
- `PUT /packages/{packageId}`: Update package
- `DELETE /packages/{packageId}`: Delete package

### Products
- `GET /products`: List all products
- `POST /products`: Create a new product
- `GET /products/{productId}`: Get specific product
- `PUT /products/{productId}`: Update product
- `DELETE /products/{productId}`: Delete product

### Blogs
- `GET /blogs`: List all blog posts
- `POST /blogs`: Create a new blog post
- `GET /blogs/{blogId}`: Get specific blog post
- `PUT /blogs/{blogId}`: Update blog post
- `DELETE /blogs/{blogId}`: Delete blog post

## External API Integrations

- **Mapbox**: Interactive maps for adventure locations
- **OpenWeather**: Weather forecasts for destinations
- **Stripe**: Secure payment processing
- **EmailJS**: Email notifications for bookings and updates

