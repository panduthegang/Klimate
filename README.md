# Klimate
<div align="center">
  <br />
    <a href="https://yourappurl.com" target="_blank">
    <img src="public/Cover 1.png" alt="Project Banner">
    </a>
  <br />

  <div>
     <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="reactjs" />
     <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="typescript" />
     <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
     <img src="https://img.shields.io/badge/-Tanstack_Query-black?style=for-the-badge&logoColor=white&logo=react-query&color=FF4154" alt="tanstackquery" />
     <img src="https://img.shields.io/badge/-OpenWeather_API-black?style=for-the-badge&logoColor=white&logo=openweathermap&color=FFDD44" alt="openweather" />
  </div>

<h3 align="center">Weather App</h3>
   <div align="center">
     Get real-time weather updates and forecasts for your favorite cities  
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🌤️ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🚀 [Quick Start](#quick-start)

## 🌤️ Introduction <a name="introduction"></a>

A weather application that provides real-time weather data for various cities. Built with React JS and TypeScript, it leverages the OpenWeather API to fetch accurate weather data, and uses Tanstack Query for efficient data fetching and caching. The application includes modern UI components with Tailwind CSS, Recharts for data visualization, and ShadCN UI for a seamless, user-friendly experience.

## ⚙️ Tech Stack <a name="tech-stack"></a>

 **React JS**
- **TypeScript**
- **Tanstack Query**
- **OpenWeather API**
- **Recharts**
- **TailwindCSS**
- **ShadCN UI**

## 🔋 Features <a name="features"></a>

👉 **Search History**: Easily access previously searched cities to quickly check the weather again.  
👉 **Mark Favorite Cities**: Mark and access favorite cities instantly for weather updates.  
👉 **Light/Dark Mode**: Switch between light and dark themes for a comfortable viewing experience.  
👉 **5-Day Forecast**: Get a 5-day weather forecast including temperature, humidity, and wind conditions.  
👉 **Real-time Data Visualization**: Display temperature and other weather parameters with Recharts for better insights.  
👉 **Detailed Weather Information**: View weather details such as wind direction, speed, humidity, and more.  
👉 **Responsive Design**: User interface optimized for devices of all sizes, ensuring accessibility on mobile, tablet, and desktop.  


## 🚀 Quick Start <a name="quick-start"></a>

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/panduthegang/Klimate.git
cd Klimate
```
**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_OPENWEATHER_API_KEY=""
```

Replace the values with your actual OpenWeather credentials. You can obtain these credentials by signing up &
creating a new project on the [OpenWearher website](https://openweathermap.org/api).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.
