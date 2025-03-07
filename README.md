# ![image](https://github.com/user-attachments/assets/154dafe4-0a92-43fc-a77e-0ca448ef1408) Google-Contacts-Integration

# Google Contacts API Integration with Spring Boot and Thymeleaf

## Objective
The objective of this task was to integrate the Google Contacts (People) API into a Spring Boot application with a Thymeleaf-based user interface. The application allows users to authenticate via Google, retrieve their contact lists, and perform CRUD (Create, Read, Update, Delete) operations on their Google Contacts.

---

## Implementation Steps

### 1. Setting Up Google API Credentials
- Created a Google Cloud project and enabled the People API.
- Generated OAuth 2.0 credentials (Client ID and Secret) for authentication.
- Configured the OAuth consent screen with necessary scopes:  


### 2. Backend Development (Spring Boot)
- Implemented authentication using OAuth 2.0.
- Developed RESTful endpoints for:
- Retrieving all contacts from the authenticated user's Google Contacts.
- Adding new contacts.
- Editing existing contacts.
- Deleting contacts.
- Configured Spring Security for authentication and token management.

### 3. Frontend Development (Thymeleaf UI)
- Designed a user-friendly interface to display contacts.
- Created forms for adding and editing contacts.
- Implemented buttons for updating and deleting contacts.

### 4. Testing and Deployment
- Verified OAuth authentication and tested CRUD operations.
- Debugged API request failures and authentication issues.
- Configured environment variables securely for deployment.

---

## Challenges Encountered and Solutions

### 1. OAuth 2.0 Authentication Issues
**Challenge:** Incorrect redirect URIs or missing scopes caused authentication failures.  
**Solution:** Ensured correct redirect URIs in Google Cloud console and verified granted scopes.

### 2. Handling API Rate Limits
**Challenge:** Google enforces rate limits on API requests.  
**Solution:** Implemented exponential backoff and caching mechanisms.

### 3. Updating Contacts Not Reflecting Immediately
**Challenge:** API changes were not reflecting instantly.  
**Solution:** Implemented request handling with refresh mechanisms.

### 4. CSRF Protection in Spring Security
**Challenge:** CSRF protection blocked API calls.  
**Solution:** Configured Spring Security to handle CSRF tokens appropriately.

---

## Conclusion
This project successfully integrated the Google Contacts API with a Spring Boot application using a Thymeleaf UI. Users can authenticate with Google, view their contacts, and perform CRUD operations seamlessly. The challenges faced were resolved through debugging and best practices in API integration.



## Developer Profiles  
Meet the amazing developers behind!  

- **[Alyssa Blanche S. Alivio](https://github.com/OliGwapa)**  
---

