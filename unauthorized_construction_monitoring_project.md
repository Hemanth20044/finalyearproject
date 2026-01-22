# Unauthorized Construction Monitoring and Reporting System

## Project Overview
This project is a **web-based application** designed to monitor, report, and view **unauthorized constructions**. It integrates government land data with citizen-reported complaints to improve transparency and help authorities identify illegal constructions.

---

## Objectives
- Monitor unauthorized constructions near lakes and buffer zones
- Allow citizens to report illegal constructions with images and location
- Provide verified government land and lake data for reference
- Increase public awareness and transparency

---

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP / WAMP)

---

## System Modules

### 1. Home Page
- Acts as the landing page
- Introduces the concept of unauthorized construction monitoring
- Provides navigation to other modules

---

### 2. Unauthorized Construction Data Module
- Displays official government data such as:
  - District
  - Mandal
  - Village
  - Lake Name & ID
  - FTL Map
  - Cadastral Map
  - Buffer Zone Details
- Data is fetched dynamically from the database using PHP

---

### 3. Report Unauthorized Construction Module
- Allows users to submit complaints
- User inputs include:
  - Name
  - Email
  - Location
  - Description
  - Image upload
- Uploaded images are stored on the server
- Complaint details are saved in the database

---

### 4. News / Reports Feed Module
- Displays all reported unauthorized constructions
- Shows image, location, description, and date
- Works like a public news feed

---

## Database Design

### Table: `reports`
| Field Name | Description |
|----------|------------|
| id | Unique report ID |
| name | Reporter name |
| email | Reporter email |
| location | Construction location |
| description | Issue details |
| image_path | Uploaded image path |
| created_at | Date and time |

---

## Advantages
- Encourages citizen participation
- Improves transparency
- Helps authorities detect illegal constructions
- Easy-to-use interface

---

## Real-World Applications
- Municipal Corporations
- Urban Development Authorities
- Environmental Protection Agencies
- Smart City Initiatives

---

## Future Enhancements
- Google Maps integration
- Admin login and verification system
- Automated alerts to authorities
- AI-based image validation
- Mobile application

---

## Conclusion
This project provides an effective platform for monitoring and reporting unauthorized constructions by combining government data with citizen involvement, helping protect land and water resources.

---

## Viva One-Liner
> *This project is a web-based system that enables reporting and monitoring of unauthorized constructions using official land data and user-submitted evidence.*