# 🌍 Tripnexa

**Tripnexa** is a full-stack travel and accommodation platform where users can explore, view, and manage travel listings. The project provides a user-friendly interface for discovering destinations and managing listings, reviews, and user accounts.

 🚀 Live Demo

🔗 Live Website:** [https://tripnexa.onrender.com/listings]

## 📸 Features

* 🔐 User authentication and authorization
* 🏠 Create, edit and delete travel listings
* 🔍 Browse and explore different listings
* 📍 Location-based listing information
* 🗺️ Interactive map integration
* ⭐ Add and delete reviews
* ☁️ Image upload and cloud storage
* 💰 Dynamic price display
* 📱 Responsive user interface
* ⚠️ Server-side and client-side validation
* 🔒 Protected routes for authenticated users

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* EJS
* Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Services

* Passport.js
* Passport Local
* Cloudinary
* Mapbox

### Deployment

* Render
* Git & GitHub

## 📂 Project Structure

```text
Tripnexa/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── middleware.js
├── app.js
├── schema.js
├── package.json
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/shravan-kumargupta/Tripnexa.git
cd Tripnexa
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create environment variables

Create a `.env` file in the root directory:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_api_secret
MAP_TOKEN=your_mapbox_token
```

> Never commit your `.env` file or expose API keys and secrets publicly.

### 4. Start the application

```bash
node app.js
```

For development with Nodemon:

```bash
nodemon app.js
```

The application will run on:

```text
http://localhost:8080
```

## 🎯 What I Learned

Through this project, I gained practical experience in:

* Building a full-stack web application
* RESTful API and routing
* CRUD operations
* MongoDB database management
* Mongoose schemas and relationships
* Authentication and authorization
* Express middleware
* Image uploading with Cloudinary
* Map integration and geocoding
* Form validation
* Error handling
* MVC architecture
* Git and GitHub
* Deploying a Node.js application

## 🔮 Future Improvements

* Add advanced search and filtering
* Add wishlist/favorite functionality
* Improve booking functionality
* Add payment integration
* Add user profile dashboard
* Improve mobile responsiveness
* Add more personalized travel recommendations

## 👨‍💻 Author

**Shravan Kumar **

B.Tech CSE Student | Full-Stack Developer

* GitHub: [shravan-kumargupta](https://github.com/shravan-kumargupta)
* LinkedIn: [Shravan Kumar Gupta](https://www.linkedin.com/in/shravankumargupta/)

---

⭐ If you find this project useful, consider giving it a star!
