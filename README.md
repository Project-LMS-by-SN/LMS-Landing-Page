# Landing Page of LMS
This is a Landing Page for LMS.


# Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/Project-LMS-by-SN/LMS-Landing-Page.git
```

---

## 2. Change your Directory

```bash
cd LMS-Landing-Page
```
---
## 3. Install Dependencies

```bash
npm install
```
---

## 4. Setup .env File
Create a .env File

```bash
# Backend Server Port
PORT=5000

# MongoDB Connection URI (Atlas)
# Replace with your actual MongoDB Atlas connection string:
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/lms?retryWrites=true&w=majority

# Optional: Custom DNS for local development (resolves querySrv ECONNREFUSED on local ISP)
DNS_SERVERS=1.1.1.1,1.0.0.1

```
## 5. Start the Application

Start Frontend (Vite):
```bash
npm run dev
```

Start Backend Server:
```bash
npm run server
```
