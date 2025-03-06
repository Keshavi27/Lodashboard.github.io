# LeadOrchard Dashboard  

## 🚀 Project Overview  
LeadOrchard Dashboard is a powerful AI-driven platform designed to streamline small-scale city services like home services, hospitality, and more. It provides a seamless experience for businesses by managing appointment scheduling, organizational data, and AI-based customer interactions.  

At the core of LeadOrchard is **Availably**, an AI ML-powered voice assistant that engages customers when human agents or voicemail systems are unavailable. Availably is trained using datasets provided by companies registered on the platform, enabling it to deliver precise and relevant responses.  

---

## 🛠️ Tech Stack  
### **Backend (Server-side)**
- **Python Django** – Powers the backend with robust API support.  
- **Django Rest Framework (DRF)** – Provides APIs for seamless frontend integration.  
- **Linode Virtual Machine (VM)** – Hosting and deployment of the backend services.  

### **Frontend (Client-side)**
- **React.js** – Ensures a dynamic and responsive user interface.  


## 🔥 Key Features  
- **Organization & User Management** – Companies register on the platform and manage multiple users.  
- **AI Voice Assistant (Availably)** – Automates responses and customer interactions.  
- **Custom API Development** – Built using Django's `ModelViewSet` and `ModelSerializer` for efficient CRUD operations.  
- **Advanced Middleware & Permissions** – Ensures security, request handling, and seamless access control.  
- **Dynamic Category & Subcategory System** – Hierarchical categorization for better service classification.  
- **Self-Learning AI Models** – Uses organizational datasets to train AI for customer service automation.  



## 📌 Project Architecture & Workflow  
1. **Organization Registration & User Creation**  
   - A new organization registers, and an admin user is assigned.  
   - Users within an organization have roles (Admin or Normal User).  

2. **Category & Subcategory Management**  
   - Parent-Child relationships between categories allow dynamic structuring.  

3. **AI Training Data Integration**  
   - Companies provide datasets: introductory prompts, knowledge bases, Q&A repositories.  
   - The AI model (GPT-based) learns and responds based on these datasets.  

4. **Middleware & Authentication**  
   - Middleware extracts `organization ID` from request headers.  
   - Permissions are enforced to ensure secure access.  

5. **Data Storage & API Management**  
   - Organizational data (phone numbers, addresses) is securely stored.  
   - Django Rest Framework APIs handle CRUD operations.  



## 🎯 My Contributions (Backend Development)  
As the **Backend Developer**, I was responsible for designing and implementing the following:  

✅ **API Development:** Created Django Rest Framework APIs using `ModelViewSet` and `ModelSerializer`.  
✅ **Custom Middleware:** Implemented middleware to extract `organization ID` from request headers.  
✅ **User & Organization Models:** Designed database models with a **one-to-many** relationship (one organization, multiple users).  
✅ **Authentication & Role-Based Access Control:** Created permission classes for Admin and Normal Users.  
✅ **AI Integration:** Helped structure the training dataset for Availably’s AI model.  
✅ **Deployment on Linode VM:** Set up and configured the backend on Linode.  

---

## 🏗️ Django Concepts Used  
- **CustomUser/AbstractUser** – Extending Django’s default user model.  
- **Self-Referencing Models** – Implementing hierarchical categories.  
- **ModelViewSet & ModelSerializer** – Optimized API development.  
- **Middleware** – Custom processing of requests and responses.  
- **Mixins** – Reusable logic for querysets and authentication.  
- **URL Routing** – Proper endpoint structuring for API accessibility.  

