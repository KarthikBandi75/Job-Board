# 🎯 Job Portal - Internship & Job Application Management System

A fully-featured **MERN Stack** based web application with dedicated portals for **Users (Students), Employers, and Admins**. This system enables streamlined internship and job management, company profile creation, user applications, real-time application status updates with email notifications, OTP authentication, and comprehensive admin controls.

---

## 🚀 Live Deployments

- 👩‍💼 **Admin/Employer Portal:** [https://jobs-admin-employee-frontend.vercel.app/login](https://jobs-admin-employee-frontend.vercel.app/login)
- 🧑‍🎓 **User Portal:** [https://jobs-user-frontend.vercel.app/](https://jobs-user-frontend.vercel.app/)

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** Email-based OTP Verification
- **Email Service:** Nodemailer (or similar)
- **Deployment:** Vercel for frontend, Render/Heroku for backend (assumed)
- **Architecture:** Modular & Component-Based, Fully Responsive Design

---

## 👥 Roles & Features

### 🧑‍🎓 User (Student)

- ✅ Sign Up with Email OTP verification
- 🔐 Secure OTP Login every time
- 📝 Create & update full profile (acts as resume)
- 📄 Upload resume as PDF
- 🧑‍💼 Browse all job/internship postings
- 📬 Apply to roles (one-time per job)
- 🔁 Withdraw & re-apply to jobs
- 📊 View application status: `Pending`, `Selected`, or `Rejected`
- 📧 Real-time Email notifications for status updates

---

### 👨‍💼 Employer

- 🔐 Register/Login
- 🏢 Create/Update company profile (with image/logo)
- 📋 Post, Update, and Delete Jobs/Internships
- 👀 View all applicants per job, including resume PDFs and user profiles
- 🔁 Update application status (`Selected`, `Rejected`, `Pending`)
- 📈 Dashboard metrics: total jobs posted, applications received
- 📧 Email notifications sent automatically on status change

---

### 🛡️ Admin

- 🔐 Login with fixed secure credentials
- 👥 View all users, employers, and jobs
- ❌ Delete any user, employer, or job
- ⚠️ Mark jobs as `Suspicious` or `Inactive`
- 📊 View global metrics (platform-wide analytics)

---

## 📱 Responsive Design

- 💻 Fully responsive UI for **Mobile**, **Tablet**, and **Desktop**
- Optimized for all modern browsers
- Clean and minimal Tailwind CSS-powered interfaces

--

