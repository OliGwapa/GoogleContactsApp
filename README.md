# ![image](https://github.com/user-attachments/assets/154dafe4-0a92-43fc-a77e-0ca448ef1408)
Google-Contacts-Integration

Google Contacts/People API Integration

## Objective:

The objective of this task was to integrate the Google Contacts (People) API into a Spring Boot application with a Thymeleaf-based user interface. The application allows users to authenticate via Google, retrieve their contact lists, and perform CRUD (Create, Read, Update, Delete) operations on their Google Contacts.


## Implementation Steps:

<details>
1.) Setting Up Google API Credentials:

A Google Cloud project was created, and the People API was enabled.

OAuth 2.0 credentials (Client ID and Secret) were generated for authentication.

The OAuth consent screen was configured with necessary scopes (https://www.googleapis.com/auth/contacts). 

</details>

<details>
  <summary>🔍 <strong>Search Functionality</strong></summary>

  - **Complete pet profiles** (breed, age, health info) are required before searching.  
  - Results will **only show pets** that match the user’s **search criteria** (breed, age, location, etc.).  
  - **Search filters** can be adjusted, but **core criteria** (breed, health, location) **must always be included**.  
  - Only pets in **good health** with **verified vaccinations** can be listed for matchmaking.  

</details>

<details>
  <summary>📝 <strong>CRUD (Create, Read, Update, Delete)</strong></summary>

  - Only **registered users with verified accounts** can create and update pet profiles.  
  - Profiles must have **honest and accurate information**—false details may lead to **removal or suspension**.  
  - Users **can only delete their own pet profiles**—deletions are **permanent**.  
  - Profile updates require **admin approval** for critical details like **breed or health status**.  
  - Admins **periodically review** pet profiles for **compliance with platform standards**.  

</details>

<details>
  <summary>📅 <strong>Scheduling</strong></summary>

  - Appointments must be scheduled **at least 48 hours in advance**.  
  - Users can’t schedule **more than one appointment per pet in 24 hours**, unless agreed upon.  
  - **Cancellations require 24-hour notice**—failure to comply may result in **penalties**.  
  - All meetings must **follow local breeding laws** and **health standards**.  

</details>

<details>
  <summary>🔮 <strong>Prediction</strong></summary>

  - Predictions are based on **user-provided data** (breed, health, age). Accuracy depends on **up-to-date information**.  
  - Predictions serve as **recommendations only**—owners should still **research and consult experts**.  
  - The **algorithm is updated regularly** for better accuracy.  
  - Users **aren't obligated** to follow predictions—**final decisions lie with pet owners**.  

</details>

<details>
  <summary>🔔 <strong>Reminders & Notifications</strong></summary>

  - Users can **opt in or out** of notifications (appointments, health reminders, updates).  
  - Notifications are sent via **in-app alerts, email, or SMS**, based on preferences.  
  - Users must **keep contact details updated** for timely alerts.  
  - Reminders are based on **user input** and can’t be changed without approval.  
  - Repeated **missed appointments** may lead to **account penalties**.  

</details>

---

## 🔗 Quick Links  

### 🎨 Figma Design  
[![View on Figma](https://img.shields.io/badge/Figma-Design-blue?style=for-the-badge&logo=figma)](https://www.figma.com/design/kCBz0xtZ5OmNyWHyL6bnDL/Pawfect-Match?node-id=0-1&t=VhLdwzYjh35VQNhM-1)  

### 📊 Entity Relationship Diagram  
[![View ERD](https://img.shields.io/badge/View%20ERD-Diagram-green?style=for-the-badge&logo=database)](https://online.visual-paradigm.com/share.jsp?id=333535313236382d32)  

---

## 👩‍💻 Developer Profiles  
Meet the amazing developers behind **Pawfect Match**!  

- **[Alyssa Blanche S. Alivio](https://github.com/OliGwapa)**  
- **[Genesis T. Clabisellas](https://github.com/clabisellasg)**  
- **[Jannah Lovelle B. Sendrijas](https://github.com/jannahlovelle)**  

---

