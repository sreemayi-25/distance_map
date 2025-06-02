# 🌍 Distance Calculator Web App

This is a simple and responsive web application that lets users select **two places** and calculates the **distance** between them using the **Google Maps API**. The application provides real-time suggestions for locations and displays both the **calculated distance** and a **visual route** on the map.

---

## 🚀 Features

- 🔎 **Autocomplete** input for both locations using Google Places API  
- 📍 **Map rendering** with route displayed between the selected points  
- 🧮 **Accurate distance calculation** in kilometers (or miles, if configured)  
- 💻 **Responsive design** for mobile and desktop  
- 🧊 Clean and minimal UI

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (Vanilla JS)  
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/overview)  
- [Google Places API](https://developers.google.com/maps/documentation/places/web-service/overview)  
- Bootstrap (optional)

---

## 📦 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/distance-calculator.git
   cd distance-calculator
``

2. **Create a Google Maps API Key**

   * Go to [Google Cloud Console](https://console.cloud.google.com/)
   * Enable Maps JavaScript API & Places API
   * Create an API key

3. **Add your API key**
   Open `index.html` and replace `YOUR_API_KEY_HERE` with your actual key:

   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY_HERE&libraries=places"></script>
   ```

4. **Open in browser**
   Simply open `index.html` in any browser to start using the app.


---

## 💡 Future Improvements

* Add distance in miles as an option
* Show travel time based on transportation mode
* Support multiple route options
* Deploy online using GitHub Pages or Netlify

---

