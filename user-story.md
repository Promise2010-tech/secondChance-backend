# Second Chance Project - Product Backlog

## Immediate Sprint Backlog (Label: backlog)

### 1. Finish user stories
**As a** Product Owner  
**I need** a structured sprint plan  
**So that** the development team understands immediate deliverables.  
* **Acceptance Criteria:** Given a set of project requirements, when triaged into issues, then at least 8 user stories must be visible.

### 2. Initialize and populate MongoDB
**As a** Backend Developer  
**I need** to configure a local database instance  
**So that** application collection assets persist securely.  

### 3. Run skeleton application
**As a** Backend Developer  
**I need** to launch the base Node.js server loop  
**So that** API network endpoints listen cleanly on port 3000.  

### 4. Implement SecondChanceItems service API
**As a** Client Application  
**I need** to access dedicated CRUD endpoints  
**So that** donation items can be created, read, updated, and deleted.  

### 5. Implement Search service API
**As a** End User  
**I need** to filter items by keyword and category  
**So that** I can find specific donation items instantly.  

### 6. Implement Sentiment Analysis service API
**As a** Content Moderator  
**I need** to evaluate description text sentiment automatically  
**So that** inappropriate or toxic descriptions are flagged.  

### 7. Implement Registration backend service API
**As a** New User  
**I need** to sign up with email and password  
**So that** a secure personal profile account is written to the database.  

### 8. Implement Login backend service API
**As a** Returning User  
**I need** to submit authentication credentials  
**So that** a secure session token is generated.  

### 9. Implement User Profile backend service API
**As a** Registered User  
**I need** to update my account details  
**So that** my contact information stays accurate.  

---

## Future Deliverables (Label: icebox)

### 10. Integrate the frontend provided with the backend
**As a** End User  
**I need** a visual user interface linked to the APIs  
**So that** I can interact with the system smoothly.  

### 11. Add CI/CD pipelines for backend services
**As a** DevOps Engineer  
**I need** automated test and build workflows  
**So that** broken code changes are blocked before production.  

### 12. Containerize the services and applications
**As a** Systems Administrator  
**I need** to isolate application processes inside Docker  
**So that** deployment environments remain entirely uniform.  

### 13. Deploy backend services
**As a** Cloud Engineer  
**I need** to host the containerized backend services on a cloud provider  
**So that** the application endpoints stay highly available.  

---

## Technical Debt (Label: technical debt)

### 14. Research authentication in Express
**As a** Security Architect  
**I need** to review modern middleware authentication mechanisms  
**So that** user sessions are protected against vulnerabilities.  
