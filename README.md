# haz_rep

# Road Hazard Reporting App

A web-based application to report, track, and manage road hazards in your locality.

---

## Features

- **User Features**
  - Report road hazards with a photo and location.
  - Add optional captions for more details.
  - View hazards on an interactive map.

- **Admin Features**
  - Login authentication for admins.
  - Review, approve, or reject reported hazards.
  - Manage hazards via a dashboard.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd road-hazard-app
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Set up the database:
   ```bash
   rails db:create db:migrate
   ```

4. Start the server:
   ```bash
   rails server
   ```

5. Open the app in your browser:
   ```
   http://localhost:3000
   ```

---

## Checklist

### **1. Setup**
- [x] Install Ruby on Rails and necessary dependencies.
- [ ] Set up the project and initialize the database.

### **2. User Features**
- [ ] Create a hazard reporting form.
- [ ] Enable photo uploads.
- [ ] Capture location data.
- [ ] Save and display hazard reports.
- [ ] Integrate a map to display hazards.

### **3. Admin Features**
- [ ] Implement admin login authentication.
- [ ] Build an admin dashboard to view reports.
- [ ] Add approve/reject functionality.
- [ ] Allow filtering of reports by status.

### **4. Testing and Deployment**
- [ ] Test all forms and features.
- [ ] Debug and fix any issues.
- [ ] Deploy the app to a hosting platform.

### **5. Optional Enhancements**
- [ ] Add geolocation to auto-fill location.
- [ ] Send notifications to admins for new reports.
- [ ] Enable user search and filtering.

---

