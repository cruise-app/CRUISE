# CRUISE

A mobile application designed to offer smart transportation solutions. It offers **carpooling, car rentals, AI-powered safety features, chatbot customer support, SIEM solutions**, and **admin dashboards** for full system control and monitoring. The platform is designed with a focus on safety, simplicity, and eco-friendliness, enabling users to easily find rides or rent cars while reducing traffic and emissions.

---

## Demo Video

Click the image to watch our demo on YouTube:

[![Watch the Demo](https://github.com/user-attachments/assets/f2c51296-7bba-4add-98d4-b160818b73af)](https://youtu.be/b51T0bK5jm0)

## Features

### 1. **Carpooling**
- Create or join a ride with people going to the same destination.
- Matching based on **location, time, and route**.

### 2. **AI Safety Features**
- **Record partitions** of in-ride conversations.
- **Speech-to-text transcription** of the conversations.
- Detects **hate speech** or offensive language.
- **Real-time alerts** sent to trusted contacts via SMS and Email.
- **Stores audio** for evidence.
- Detects **route deviations** to flag suspicious behavior.

### 3. **Car Rental**
- Rent cars directly from other users by **area, date, and time**.
- View details of the car offered.

### 4. **Blog Section**
- Add posts, likes, and comments on images and thoughts about the trip.
- View the following, followers, and previous posts.

### 5. **Chatbot Assistant**
- Helps users with **booking**, **ride search**, **reporting issues**, and **alerting emergency contacts**.

### 6. **Admin Pages**
- Full admin control panel for managing the application and test reports of the backend.
- Add, edit, or delete entries from the database.
- Includes two dashboards:
  - **Business Dashboard**: [Access it here](https://charts.mongodb.com/charts-project-0-kbcxtjq/public/dashboards/685ea23a-2404-4915-8da5-d6ec8beb41f8).
  - **Developer Dashboard**: [Access it here](https://charts.mongodb.com/charts-project-0-whlqmxl/public/dashboards/67677d9e-2b97-45ce-8540-ae585dfc1477).

### 7. **SIEM Integration**
- Connected with a **Security Information and Event Management (SIEM)** system to detect suspicious login attempts.
- Send alerts via Telegram and block the IP address of the attacker
- Enables **incident investigation** by Wazuh dashboard.

---

## Repository Structure

This repository includes submodules, including a specific part of the application:

```

/CRUISE
├── /cruise-mobile         # Flutter mobile application
├── /cruise-backend        # Node JS backend services
├── /cruise-ai             # AI models (speech recognition, Hate classification, Chatbot)
├── /cruise-admin          # Admin pages and control dashboard

````

---

## Meet the Team

![IMG-20250704-WA0070](https://github.com/user-attachments/assets/522a8662-fe74-41d3-ae93-fb39dedbc25e)

We are a group of final-year students from the **College of Computing and Information Technology at AASTMT Cairo**. CRUISE is our graduation project for the academic year 2024/2025. We are proud to have earned an **A+ grade** for our graduation project (**CRUISE**).

### **Team Members** (from right to left):

| Member Name        | Role                                |
| ------------------ | ----------------------------------- |
| **Nour Youssri**   | Backend Engineer                    |
| **Ali El-Saeed**     | AI and Data Engineer                |
| **Adham Montaser** | Cybersecurity, Backend Engineer     |
| **Zeyad Tamer**    | AI Engineer, Backend Engineer       |
| **Mohamed Emad**   | Flutter Developer, Backend Engineer |
