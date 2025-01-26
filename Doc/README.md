
# CarthageBot


We aim to simplify university life for IHEC Carthage students by addressing their most common questions and providing guidance to navigate academic and extracurricular challenges. Through our support, students can focus on achieving their goals while seamlessly adapting to university life.

## Authors

- [@skan45](https://github.com/skan45)
- [@tarek-gritli](https://github.com/tarek-gritli)
- [@mohamedaminehamdi](https://github.com/mohamedaminehamdi)
- [@abderrahmen bejaoui](https://github.com/abderbj/abderbj)

![Logo](images/logo.png)

## Features

### User-Focused Features:
- **Keyword-Based Search System**: 
   - Allows students to search for resources and answers by keywords for quick navigation.
- **Guided Navigation**: 
   - Directs students to the most relevant resources, such as schedules, forms, or campus information.
- **Fullscreen Mode**: 
   - Optimized for immersive interaction and ease of use during assistance sessions.
- **Cross-Platform Support**: 
   - Accessible on multiple platforms including mobile, desktop, and tablets.
- **Multilingual Chatbot (French & English)**: 
   - Tailored to assist new students at IHEC with information about courses, campus services, and administrative procedures, ensuring inclusivity for French and English speakers.
- **Feedback System**: 
   - Empowers students to rate chatbot responses, providing a continuous improvement mechanism.

### Admin-Focused Features:
- **Notification System**: 
   - Alerts the admin about flagged responses or reports of inaccurate answers, ensuring timely intervention and quality control.
- **Admin Dashboard**: 
   - A dedicated interface for the IHEC administration to manage and optimize the chatbot:
     - Add, delete, or update prompts to keep the knowledge base relevant.
     - Monitor flagged responses and provide corrective actions.
- **Data View & Performance Visualization**: 
   - Offers detailed insights into chatbot performance, including:
     - Most frequently asked questions.
     - User interaction patterns.
     - Areas where the chatbot struggles, allowing data-driven improvements.

### Localized and Contextual Aspects:
- **IHEC-Specific Focus**: 
   - The chatbot and dashboard are designed specifically for IHEC's needs, ensuring it provides highly relevant and localized information to students.
   - Examples include:
     - Directions to IHEC Tunis offices and departments.
     - Help with registration procedures unique to IHEC.
     - Guidance on local campus activities, events, and student services.
- **Custom Dataset Management**: 
   - The admin can continuously refine the chatbot’s dataset by:
     - Adding new questions about local policies, services, and events.
     - Deleting outdated or irrelevant information.
     - Updating responses to reflect the most current campus offerings.

This system ensures that students have a reliable, localized, and up-to-date digital assistant, while IHEC administration retains full control to adapt and enhance the experience as needed.
# Project Setup

## Run Locally

### Clone the Project Repositories

1. **Backend and Chatbot**:
   ```bash
   git clone https://link-to-backend-repo
   ```

2. **Frontend App**:
   ```bash
   git clone https://link-to-frontend-repo
   ```

3. **Admin Dashboard**:
   ```bash
   git clone https://link-to-admin-dashboard-repo
   ```

---

### Backend and Chatbot

1. Navigate to the backend directory:
   ```bash
   cd backend-project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the backend application:
   ```bash
   python app.py
   ```

---

### Frontend App

1. Navigate to the frontend directory:
   ```bash
   cd frontend-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend app:
   ```bash
   npm start
   ```

---

### Admin Dashboard

1. Navigate to the admin dashboard directory:
   ```bash
   cd admin-dashboard-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the admin dashboard:
   ```bash
   npm start
   

## API Reference

#### prompt the chatbot

   **API Endpoints:**
   - **Chat:** `http://localhost:5000/chat`

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `message` | `string` | **Required**. the user question |

#### give the feedback to the admin

**Frontend App Endpoints:**
   - **Notifications:** `http://localhost:3001/notifications`



