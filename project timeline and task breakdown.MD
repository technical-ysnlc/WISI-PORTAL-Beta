# 📌 WISI Recruitment & Management System

**Project Timeline & Development Tasks**
Platform: WordPress + JetEngine + Elementor Pro

---

## 🧩 PROJECT OVERVIEW

A full Recruitment and Applicant Management System designed for WISI Agency, including:

* Applicant Registration
* Admin Dashboard
* Applicant Tracking
* Status Management
* Automated ID Generation
* Reporting & Exporting

---

# 🚀 PHASE 1: PROJECT SETUP

### ✅ Environment Setup

* [ ] Install WordPress (Local + Live Server)
* [ ] Install and activate required plugins:

  * [ ] JetEngine
  * [ ] JetFormBuilder
  * [ ] Elementor Pro
  * [ ] Crocoblock dependencies
* [ ] Configure Permalinks (Post name)
* [ ] Setup User Roles (Admin, Staff, Applicant)

---

# 🗄️ PHASE 2: DATABASE ARCHITECTURE (JetEngine)

### ✅ Custom Post Types / CCT

* [ ] Create **Applicant List (CCT)**
* [ ] Create **Employers (CPT/CCT)**
* [ ] Create **Job Categories (CCT)**
* [ ] Create **Statuses (CCT)**

### ✅ Meta Fields (Applicant)

* [ ] Applicant ID (custom format: 81-YYYY-XXXXX)
* [ ] First Name
* [ ] Middle Name
* [ ] Last Name
* [ ] Full Name (auto-generated)
* [ ] Date of Birth (timestamp)
* [ ] Age (auto-calculated)
* [ ] Gender
* [ ] Contact Number
* [ ] Email Address
* [ ] Address
* [ ] Photo (2x2 format)
* [ ] Status (Pending / Approved / Rejected)
* [ ] Assigned Staff
* [ ] Date Applied

---

# ⚙️ PHASE 3: BACKEND LOGIC & AUTOMATION

### ✅ Custom Hooks / Functions

* [ ] Generate Applicant ID (auto-increment with prefix)
* [ ] Prevent duplicate Applicant ID (race condition handling)
* [ ] Auto-generate Full Name (Firstname + Middlename + Lastname)
* [ ] Auto-calculate Age from Date of Birth
* [ ] Assign default Status = Pending

### ✅ Validation Rules

* [ ] Required fields validation
* [ ] Email format validation
* [ ] Duplicate submission prevention
* [ ] File upload validation (image only, 2x2 ratio)

---

# 📝 PHASE 4: FORM CREATION (JetFormBuilder)

### ✅ Applicant Registration Form

* [ ] Personal Information Section
* [ ] Contact Information Section
* [ ] Upload Photo with crop support (2x2)
* [ ] Hidden Fields:

  * [ ] Full Name
  * [ ] Applicant ID
  * [ ] Submission Timestamp

### ✅ Form Features

* [ ] AJAX Submission
* [ ] Success / Error Messages
* [ ] Redirect after submission
* [ ] Prevent double submission (debounce / disable button)

---

# 🎨 PHASE 5: FRONTEND UI (Elementor Pro)

### ✅ Public Pages

* [ ] Home Page
* [ ] Applicant Registration Page
* [ ] About / Info Page

### ✅ Dashboard Pages (Admin/Staff)

* [ ] Applicant List Table
* [ ] Applicant Detail View
* [ ] Edit Applicant Page

### ✅ UI Components

* [ ] Responsive Design (Desktop / Tablet / Mobile)
* [ ] Styled Forms (Elementor + Custom CSS)
* [ ] Styled Select Fields (Select2 customization)
* [ ] Status Badges (color-coded)

---

# 📊 PHASE 6: DATA DISPLAY (JetEngine Listings)

### ✅ Listings

* [ ] Applicant Table View
* [ ] Applicant Cards View (optional)

### ✅ Features

* [ ] Search & Filters
* [ ] Sort by Date / Status / Name
* [ ] Pagination
* [ ] Bulk Actions

---

# 📤 PHASE 7: EXPORT & REPORTING

* [ ] Export Applicant Data to CSV
* [ ] Filter before export
* [ ] Generate basic reports:

  * [ ] Total Applicants
  * [ ] Approved / Pending / Rejected counts

---

# 🔐 PHASE 8: USER ACCESS & PERMISSIONS

* [ ] Restrict dashboard pages to logged-in users
* [ ] Role-based access:

  * [ ] Admin (full control)
  * [ ] Staff (limited editing)
  * [ ] Applicant (view own data)

---

# 🧪 PHASE 9: TESTING & QA

* [ ] Test form submissions (no duplicates)
* [ ] Test Applicant ID generation
* [ ] Test mobile responsiveness
* [ ] Test upload + cropping
* [ ] Test filters & search
* [ ] Fix UI/UX inconsistencies

---

# 🚀 PHASE 10: DEPLOYMENT

* [ ] Backup system
* [ ] Migrate to production server
* [ ] Reconfigure database connections
* [ ] Test live environment
* [ ] Enable caching & optimization

---

# 📈 PHASE 11: POST-LAUNCH IMPROVEMENTS

* [ ] Performance optimization
* [ ] Security hardening
* [ ] Add notification system (Email/SMS)
* [ ] Add applicant tracking timeline
* [ ] Add interview scheduling module

---

# 📅 SUGGESTED TIMELINE

| Phase     | Task               | Duration |
| --------- | ------------------ | -------- |
| Phase 1–2 | Setup + Database   | 2–3 days |
| Phase 3   | Backend Logic      | 3–5 days |
| Phase 4   | Forms              | 2–3 days |
| Phase 5   | Frontend UI        | 4–6 days |
| Phase 6–7 | Listings & Reports | 3–4 days |
| Phase 8–9 | Testing            | 2–3 days |
| Phase 10  | Deployment         | 1–2 days |

**Total Estimated Time: ~2–3 Weeks**

---

# 📌 CURRENT STATUS TRACKER

* [ ] Setup Completed
* [ ] Database Ready
* [ ] Forms Working
* [ ] Backend Logic Stable
* [ ] UI Completed
* [ ] System Tested
* [ ] Live Deployment

---

# 🧠 NOTES

* Use JetEngine CCT for better performance vs CPT
* Avoid duplicate submissions via AJAX locking
* Always sanitize and validate inputs
* Keep UI clean and mobile-friendly

---

**Prepared for:** WISI Agency
**System Type:** Recruitment & Applicant Management System

---
