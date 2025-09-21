# 🏝️ NetLanka Tours – Full-Stack Tour Website

A full-stack tourism booking platform built with **React, Node.js, Express, and MongoDB**.  
Designed to help travelers explore, book, and engage with tours in **Sri Lanka**.  
Includes a secure **Admin Dashboard** for real-time content management.  

---

## 🌐 Live Demo  
🔗 [View Project](https://your-live-demo-link.com)  

---

## ✅ Features

### 🌍 Public Website
- Browse **Special Tours** & **Regular Tours** with dynamic filtering  
- **Tour Details Page** – description, images, pricing, & downloadable itinerary PDFs (via jsPDF)  
- **Booking Form** with EmailJS integration for instant inquiries  
- Floating **“Book Tour” Button** on all pages  
- **Gallery** with smooth hover/zoom effects  
- **Travel Blog** with images and optional comments  
- Responsive **Floating WhatsApp Button** for instant contact  
- Interactive **Navigation Bar** with hover animations  
- Homepage **Stats & Highlights** updated live via Admin Panel  
- **Mobile-first design** – fully responsive  

### 🔐 Admin Dashboard
- Secure login with protected routes  
- Add, Edit, Delete:  
  - ✅ Tour Packages (Special & Regular)  
  - ✅ Blog Posts  
  - ✅ Gallery Images (GridFS)  
  - ✅ Homepage content (headline, intro, visitor stats)  
- Real-time updates reflected instantly on the public site  
- Manage floating buttons & live UI elements  

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)  
![React Router](https://img.shields.io/badge/React%20Router-CA4245?logo=react-router&logoColor=white)  
![EmailJS](https://img.shields.io/badge/EmailJS-004085?logo=gmail&logoColor=white)  
![jsPDF](https://img.shields.io/badge/jsPDF-black?logo=adobeacrobatreader&logoColor=red)  
- React (Functional Components, Hooks)  
- React Router DOM (SPA navigation)  
- EmailJS (tour inquiries)  
- jsPDF (downloadable itineraries)  
- Custom CSS animations & transitions  

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node-dot-js&logoColor=white)  
![Express](https://img.shields.io/badge/Express.js-404D59?logo=express&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white)  
![Multer](https://img.shields.io/badge/Multer-yellow?logo=upload&logoColor=black)  
- Node.js + Express.js RESTful API  
- MongoDB + Mongoose ODM  
- GridFS for image storage & streaming  
- Multer for file uploads  
- dotenv for environment management  
- CORS enabled for cross-origin requests  

---

## 🗃️ Database Collections (MongoDB)

### `tours`
| Field       | Description         |
|-------------|---------------------|
| title       | Tour name           |
| location    | Tour location       |
| type        | Day Tour / Round Tour |
| duration    | Tour length         |
| rating      | Rating (1–10)       |
| price       | Price per person    |
| description | Detailed info       |
| image       | GridFS ID / Path    |

### `blogs`
| Field   | Description  |
|---------|--------------|
| title   | Blog title   |
| content | Blog content |
| image   | Blog image   |

### `gallery`
| Field       | Description        |
|-------------|--------------------|
| filename    | Image file name    |
| contentType | MIME type          |
| fileId      | GridFS ID          |

### `homecontent`
| Field  | Description               |
|--------|---------------------------|
| title  | Homepage headline         |
| intro  | Short introduction text   |
| stats  | Visitor stats/achievements|

### `comments` (optional)
| Field   | Description        |
|---------|--------------------|
| name    | Commenter’s name   |
| comment | Comment message    |

---

## 📸 Screenshots

> *(Add screenshots of homepage, tour details, booking form, and admin dashboard here)*  

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Safeeya-Munawwar/mahaweli-tours.git
   cd mahaweli-tours
