# Wanderlust 🏡🌍  
Wanderlust is a full-stack web application inspired by Airbnb, designed to provide users with a seamless platform for browsing and searching property listings based on categories and locations. This project demonstrates my proficiency in building scalable, user-friendly web applications using modern technologies.  

---

## 🚀 Features  
- **Category-Wise Listings**: Explore properties like Cabins, Beaches, Mountains, Castles, and more.  
- **Dynamic Search**: Search for properties with keyword-based filtering.  
- **Responsive Design**: Optimized for all devices, including desktops, tablets, and mobile phones.  
- **Location Integration**: Integrated **Mapbox** for location-based services.  
- **Image Management**: Securely manage property images using **Cloudinary**.  
- **Authentication**: Session-based login for personalized user experience.  
- **Scalable MVC Architecture**: Built with a clean, modular structure for maintainability.  

---

## 🛠️ Tech Stack  
- **Frontend**: EJS, HTML, CSS, Bootstrap  
- **Backend**: Node.js, Express.js, MongoDB  
- **Tools & Libraries**:  
  - **Cloudinary**: For image storage and management  
  - **Mapbox**: For location-based property listings  
  - **Sessions**: For user authentication  
  - **REST APIs**: For dynamic data handling  

---

## 🌐 Live Demo  
Check out the live application here: [Wanderlust Live App](https://wanderlust-p3e2.onrender.com)  

---

## 📂 Installation & Setup  
Follow these steps to set up the project locally:  

### Prerequisites  
Ensure you have the following installed:  
- Node.js  
- MongoDB  

### Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/kenzo0p/Wanderlust.git
   cd Wanderlust
   npm install
   npm start (http://localhost:8080)
   ```
   
2. Add .env file
- CLOUD_NAME=your_cloudinary_cloud_name  
CLOUD_API_KEY=your_cloudinary_api_key  
CLOUD_API_SECRET=your_cloudinary_api_secret  
MAP_TOKEN=your_mapbox_access_token  
SECRET=your_session_secret (any of your choice e.g your name)
ATLASDB_URL=your_mongodb_connection_uri
