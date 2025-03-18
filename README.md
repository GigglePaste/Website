---

# **Ashwa Racing Website**

## **Repository Overview**  
This repository serves as the central hub for developing and maintaining the Ashwa Racing website. It outlines a structured roadmap for building the website using **React** (frontend), **Node.js with Express** (backend), and a **database system** (MongoDB/PostgreSQL) for managing dynamic content.

---

## **Development Roadmap**

### **1. Requirements Analysis and Planning**  
- **Feature Documentation:** Define page-specific requirements:  
  - **Gallery**: Image and video showcase.  
  - **About Us**: Club history, vision, mission, team.  
  - **Projects**: Detailed dropdown for prototypes.  
  - **Recruitment**: Dynamic registration toggle.  
  - **Announcements**: Event updates.  
  - **Sponsors**: Sponsor tiers and details.  
  - **Team**: Year-wise batch details.  
  - **Contact Us**: Email and contact form.  
- **Data Models:** Identify stored data types:  
  - Media files (Gallery)  
  - Textual descriptions (About Us, Sponsors, Announcements)  
  - Project hierarchies (Projects page)  
  - Event details (Announcements page)  
- **Admin Needs:** Establish an admin interface for content updates (Announcements, Recruitment, Sponsors, etc.).  

---

### **2. Architectural Design & Tech Stack Setup**  

#### **Frontend (React)**  
- **Routing:** Implement React Router for seamless navigation.  
- **Component Structure:** Modular approach for reusable elements like the Social Footer.  

#### **Backend (Node.js & Express)**  
- **API Endpoints:**  
  - `/api/gallery`: Fetch gallery media.  
  - `/api/projects`: Serve project hierarchy.  
  - `/api/announcements`: Provide event details.  
- **Middleware:** Implement logging, error handling, and authentication for admin routes.  

#### **Database**  
- **Data Storage:**  
  - Use MongoDB for document-based data or PostgreSQL for relational structures.  
  - Define schemas for Gallery, Projects, Announcements, Sponsors, and Team.  
- **File Storage:**  
  - Utilize cloud storage or backend file management for images and videos.  

---

### **3. Backend Development (Node & Express)**  
- **Project Setup:** Initialize Node project, set up Express.  
- **Routes and Endpoints:**  
  - Design API endpoints for fetching and updating content.  
- **Database Integration:**  
  - Connect database, define models for dynamic content.  
- **Admin Controls:**  
  - Implement recruitment toggle, sponsor updates.  
- **Security & Middleware:**  
  - Body parsing, CORS handling, authentication for admin routes.  

---

### **4. Frontend Development (React)**  
- **Project Initialization:** Set up React project.  
- **Routing & Components:**  
  - Define routes for each page.  
  - Implement nested dropdowns for hierarchical data (Projects, Team).  
- **Backend Integration:**  
  - Use Axios/Fetch to retrieve data from APIs.  
- **UI/UX Improvements:**  
  - Ensure responsive design.  
  - Optimize accessibility and navigation.  
- **State Management:**  
  - Use Context API or Redux for complex interactions.  

---

### **5. Integration, Testing & Deployment**  
- **Testing:**  
  - API testing with Postman.  
  - UI testing for responsiveness and functionality.  
- **Deployment:**  
  - Host backend on Heroku/AWS.  
  - Deploy frontend on Vercel/Netlify.  
- **Maintenance & Updates:**  
  - Plan regular content updates and improvements.  

---

## **Website User Flow**  

### **1. Landing Page**  
- Hero section with banner/carousel.  
- Quick links to main pages.  
- Call-to-action buttons for recruitment and announcements.  

### **2. Global Navigation & Social Footer**  
- **Header Navigation:**  
  - Fixed menu with dropdowns for Projects and Team.  
- **Social Footer:**  
  - Persistent footer with social media links and legal info.  

---

### **3. Page Structure & Flow**  

#### **About Us**  
- Vision, mission, founder, faculty advisors, alumni.  

#### **Gallery**  
- Grid/masonry layout for media.  
- Lightbox feature for viewing images/videos.  

#### **Projects**  
- Categories: OSV, Formula Student, Moto, Hybrid, Hyperloop.  
- Nested dropdown for project types.  

#### **Recruitment**  
- Subsystem details and roles.  
- Dynamic registration button toggled via backend.  

#### **Announcements**  
- List of upcoming events.  
- Expandable details or separate pages for each announcement.  

#### **Sponsors**  
- Tier-based sponsor showcase.  

#### **Team**  
- Dropdown for selecting different batches.  

#### **Contact Us**  
- Contact details by subsystem.  
- Optional contact form.  

---

### **4. Overall Navigation & User Journey**  
- **Intuitive navigation with deep links.**  
- **Dynamic elements (recruitment button, project hierarchy dropdowns).**  
- **Responsive design for mobile and desktop.**  

---

## **Contribution Guidelines**  

### **1. Code Repository Management**  
- Developers should **fork** the repository.  
- **Pull only the code they plan to work on.**  
- **Push only their implemented changes.**  

### **2. Commit Messages & Documentation**  
- Each commit should include a **detailed message** explaining the changes.  
- Each developer should document **what** they implemented and **how.**  
- This improves integration and team collaboration.  

---
