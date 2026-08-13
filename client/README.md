# CredCheck 🎓🔒

CredCheck is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to streamline the creation, verification, and moderation of academic and professional credentials. It features role-based access control (RBAC) supporting Students, Verifiers, and Platform Admins.

---

## Features

- **Google OAuth Authentication:** Secure login for all system users.
- **Student Portal:** Create credentials and manage submissions.
- **Verifier Dashboard:** Review, approve, or reject verification requests with real-time status tracking.
- **Admin Dashboard:** Monitor platform analytics, track total users and certificates, and remove spam credentials.
- **QR Code Verification:** Generate and scan credential verification links.

---

## Tech Stack

- **Frontend:** React, Tailwind CSS, React Router DOM
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** Google OAuth

---

## Getting Started & Installation

### Prerequisites
Make sure you have installed:
- Node.js (v18+ recommended)
- MongoDB (running locally or via MongoDB Atlas)

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/credcheck.git](https://github.com/your-username/credcheck.git)
cd credcheck