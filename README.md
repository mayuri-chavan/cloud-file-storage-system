# ☁️ Cloud File Storage System

A secure, scalable, and cloud-native file storage system that allows users to upload, manage, and delete files using cloud infrastructure. Built with a focus on security, scalability, and production-ready backend architecture.

---

## 📌 Key Features

### 🔐 Authentication & Security
- Secure user authentication using JWT (JSON Web Tokens)
- Protected routes with authorization middleware
  
---

### ☁️ Cloud File Storage
- Upload files directly to Amazon Web Services S3
- Secure and scalable object storage
- Generate secure file URLs for access

---

### 📁 File Management
- Upload files (any format supported)
- Retrieve user-specific file list
- Delete files from AWS S3 + database sync
- Metadata tracking in database

---

### 🧾 Database Management
- Store file metadata in MongoDB Atlas
- Track file ownership, URLs, timestamps

---

### ⚡ REST API Architecture
- Clean and modular Express.js backend
- Fully RESTful APIs
- Middleware-based request validation

---

## 🛠️ Tech Stack

- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB Atlas
- Cloud Storage: Amazon Web Services S3
- Authentication: JWT (JSON Web Token)
- AWS SDK: AWS SDK for JavaScript v3

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/mayuri-chavan/cloud-file-storage-system.git
cd cloud-file-storage-system
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=ap-south-1
AWS_BUCKET_NAME=your_bucket_name
```

### Start Backend

```bash
npm start
```

Backend:

```text
http://localhost:5000
```

### Start Frontend

```bash
cd client
npm install
npm run dev
```

Frontend:

```text
http://localhost:3000
```

