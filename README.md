# TourScope

TourScope is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to provide users with personalized travel recommendations, hotel suggestions, and city exploration features. It integrates AI-powered recommendation systems, interactive maps, and a user-friendly interface to deliver a seamless travel planning experience.

## Features

### User Features
- **Personalized Recommendations**: AI-powered hotel and city recommendations tailored to user preferences and history.
- **Interactive Map**: Explore hotels and cities on an interactive Mapbox map.
- **Favorite List Management**: Add or remove hotels from a personal favorite list.
- **Hotel Details**: View detailed information about hotels, including ratings, location, and images.
- **Planner Integration**: Plan trips with a dedicated planner feature for exploring more cities.
- **Responsive Design**: Fully responsive UI for all devices.

### Admin Features
- **Hotel Management**: Admin panel for managing hotels, rooms, and amenities.
- **User Management**: Manage user accounts and permissions.
- **Analytics Dashboard**: View user activity, booking stats, and recommendation performance.

### AI Features
- **Recommendation System**: Uses collaborative filtering and cosine similarity to recommend hotels based on user preferences and history.
- **Data Processing**: Processes user history and hotel data to generate accurate recommendations.
- **Scalability**: AI module scales efficiently with large datasets and growing user base.

### Performance Features
- **Lazy Loading**: Optimized loading of components and data for better performance.
- **Slider Integration**: Smooth and customizable sliders for displaying recommended hotels.
- **Caching**: Caching for frequently accessed data to reduce API calls.
- **Error Handling**: Smooth fallback handling for API failures.
  
### Security Features
- **Authentication**: Secure login using JWT; supports Google and Facebook login via OAuth.
- **Data Encryption**: Sensitive data such as passwords and payments are encrypted.
- **Role-Based Access Control**: Admin features are restricted by user roles.

### Additional Features
**Booking System**: Real-time room availability, booking confirmations, and payment integration (Stripe, PayPal).
**Notifications**: Email and push notifications for bookings, recommendations, and updates.
**Reviews and Ratings**: User reviews and admin-moderated ratings for hotels.
