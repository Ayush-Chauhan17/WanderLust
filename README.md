# WanderLust 🌍

WanderLust is a full-stack web application inspired by Airbnb, where users can **explore and share campgrounds** from around the world. Users can register, log in, add new campground listings, upload photos, and leave reviews. It's designed with a focus on simplicity, usability, and clean design — perfect for nature and travel lovers!

---

## ✨ Features

- User registration & login with secure authentication
- Create, edit, and delete campground listings
- Upload multiple images using Cloudinary
- Leave and manage reviews for campgrounds
- Responsive and mobile-friendly UI
- Built using the MVC (Model-View-Controller) architecture

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS Templating Engine
- **Database:** MongoDB + Mongoose
- **Authentication:** Passport.js
- **File Uploads:** Multer + Cloudinary
- **Validation:** Joi
- **Session Storage:** connect-mongo
- **Architecture:** MVC Pattern

---

## 📸 Preview

![Homepage Preview](https://your-image-url.com/homepage.png)
> _Feel free to replace with actual screenshots or GIFs of your app UI._

---

## 🚀 Getting Started

### 1. Setup Instructions (All Steps)

```bash
# Clone the repository
git clone https://github.com/Ayush-Chauhan17/WanderLust.git
cd WanderLust

# Install dependencies
npm install

# Create a .env file in the root directory and add the following:
# (Replace the values with your own credentials)

MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
SESSION_SECRET=your_session_secret

# Now you can start your server using 
node app.js
