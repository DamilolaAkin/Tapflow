TapFlow System Architecture

Overview
TapFlow is a hybrid mobile application designed to make personal automation accessible.  
It combines a cross platform interface with a lightweight backend and real time database, ensuring fast response times and seamless user experiences.

System Layers

1. Frontend (React Native)
Role: The user interface layer where users create, customize, and trigger automations.

Responsibilities:
- Displays available templates and categories  
- Guides users through automation setup (via forms and prompts)  
- Handles local device actions (Siri triggers, notifications)  
- Syncs data with backend through RESTful APIs  

Key Components:
- Template Gallery Screen  
- Builder Wizard  
- Shortcut Trigger Module  
- User Dashboard  

 2. Backend (Node.js + Express)
Role: Acts as the logic layer processing requests, handling automation rules, and managing communication between the app and the database.

Responsibilities:
- API endpoints for user data, templates, and settings  
- Authentication and authorization (via Firebase Auth)  
- Real time updates and notifications  
- Error handling and analytics  


 3. Database (Firebase Realtime Database)
Role: Stores and syncs user data across devices in real time.

Responsibilities:
- Store user profiles and authentication tokens  
- Maintain template library  
- Store user-created shortcuts  
- Log activity and analytics for feature optimization
