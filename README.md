✅ README.md – Secure File Sharing Backend
markdown
Copy
Edit
# 🔐 Secure File Sharing API

A FastAPI-based backend for secure file sharing between **Ops** and **Client** users.  
It features JWT-based login, email verification, secure file uploads, and encrypted download links for restricted access.

---

## 🚀 Features

- ✅ Client Signup & Email Verification (Simulated)
- ✅ Ops & Client Login with JWT tokens
- ✅ Upload files (.docx, .pptx, .xlsx) — by Ops only
- ✅ View list of uploaded files — by Clients
- ✅ Request encrypted download links — by Clients
- ✅ Secure file downloads via JWT token
- ✅ Role-based access control for each route

---

## 📁 Folder Structure

file_sharing_backend/
├── app/
│ ├── main.py
│ ├── auth.py
│ ├── models.py
│ ├── schemas.py
│ ├── database.py
│ └── routers/
│ ├── client_user.py
│ └── ops_user.py
├── uploads/ ← All uploaded files
├── create_ops.py ← Adds initial Ops user
├── requirements.txt
├── README.md
└── postman_collection.json
