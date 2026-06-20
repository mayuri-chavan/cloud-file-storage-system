☁️ Cloud File Storage System

A secure, scalable, and cloud-native file storage system that allows users to upload, manage, and delete files using cloud infrastructure. Built with a focus on security, scalability, and production-ready backend architecture.

📌 Key Features

🔐 Authentication & Security
Secure user authentication using JWT (JSON Web Tokens)
Protected routes with authorization middleware
User-specific file isolation (no cross-user access)

☁️ Cloud File Storage
Upload files directly to Amazon Web Services S3
Secure, scalable object storage handling
Generate secure file URLs for access

📁 File Management
Upload files (any format support)
Retrieve user-specific file list
Delete files from S3 + database sync
Metadata tracking in database

🧾 Database Management
Store file metadata in MongoDB Atlas
Track file ownership, URLs, timestamps

⚡ REST API Architecture
Clean and modular Express.js backend
Fully RESTful endpoints for all operations
Middleware-based request validation

🛠️ Tech Stack
Frontend:
React.js
Backend:
Node.js
Express.js
Database:
MongoDB Atlas
Cloud Storage:
Amazon Web Services S3
Authentication:
JWT (JSON Web Token)
Cloud SDK:
AWS SDK for JavaScript v3


Installation:

1. Clone the Repository
git clone https://github.com/your-username/cloud-file-storage-system.git
cd cloud-file-storage-system
2. Install Dependencies
npm install
3. Setup Environment Variables

Create a .env file in the root directory:

PORT=5000

# MongoDB
MONGO_URI=your_mongodb_atlas_connection_string

# JWT
JWT_SECRET=your_jwt_secret_key

# AWS S3
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=your_region
AWS_BUCKET_NAME=your_bucket_name
4. Run the Application
npm start

Server will start at:

http://localhost:5000
