# Yelp-Camp Project

Yelp-Camp is a full-stack web application that functions as a Yelp-style platform specifically for campgrounds. This project allows users to explore, create, and interact with campground listings, providing a comprehensive environment for learning and applying web development skills.

---

## Key Features

### 1. **User Authentication**
- Users can sign up, log in, and manage their accounts securely using authentication mechanisms.
- Authentication ensures only authorized users can access certain features like creating and editing campgrounds.

### 2. **Create Campgrounds**
- Users can create new campground listings by providing:
  - A name for the campground
  - A description
  - An image (support for image uploads included)

### 3. **Commenting System**
- Users can leave comments on campground listings to share their experiences or feedback.
- This feature fosters interaction and a sense of community among users.

### 4. **CRUD Functionality**
- The application implements full CRUD (Create, Read, Update, Delete) operations for:
  - Campgrounds
  - Comments
- Users can edit or delete their own campgrounds and comments.

### 5. **Additional Features**
- **Image Uploads:** Users can upload images to accompany their campground listings.
- **Maps Integration:** Display maps for campgrounds using APIs.
- **Security Enhancements:**
  - Protection against Cross-Site Scripting (XSS)
  - Implementation of Content Security Policies (CSP)

### 6. **Deployment**
- The application is deployed to make it live and accessible to users worldwide.
- Deployment involves setting up a hosting environment and ensuring all features work seamlessly in production.

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Passport.js
- **File Storage:** Cloudinary (for image uploads)
- **Maps Integration:** Mapbox

---
## Prerequisites

Before running the application, ensure the following:
- **MongoDB:** A running instance of MongoDB (local or cloud-based) is required to store application data.
- **Node.js:** Installed on your system to run the backend server.
- **Environment Variables:** Configure required environment variables as detailed below.

---
## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/yelp-camp.git
   ```

2. Navigate to the project directory:
   ```bash
   cd yelp-camp
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     DATABASE_URL=your-mongodb-connection-string
     CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
     CLOUDINARY_API_KEY=your-cloudinary-api-key
     CLOUDINARY_API_SECRET=your-cloudinary-api-secret
     MAPBOX_TOKEN=your-mapbox-token
     ```

5. Start the development server:
   ```bash
   npm app.js
   ```

6. Visit the application in your browser at `http://localhost:3000`.

---

## Usage

- **Sign Up:** Create an account to access all features.
- **Explore Campgrounds:** Browse existing campgrounds and view details.
- **Create a Campground:** Add new campground listings with images and descriptions.
- **Comment:** Share your experiences by commenting on campgrounds.
- **Edit/Delete:** Manage your campgrounds and comments.

---

## Deployment

To deploy the application:

1. Set up a hosting environment (e.g., Heroku, AWS, or Render).
2. Configure environment variables in the hosting service.
3. Deploy the codebase and ensure all dependencies are installed.
4. Test the deployed application to verify functionality.

---


## Acknowledgements

- This project was created as part of a web development course.
- Special thanks to the course instructors and contributors for guidance and resources.

