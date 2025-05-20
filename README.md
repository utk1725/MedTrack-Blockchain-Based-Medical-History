🏥 MedTrack – Blockchain-Based Medical History Sharing System

Phase 2: Implementation & Execution
College: VIT Bhopal University
Name: Utkarsh Singh
```markdown
# MedTrack - Blockchain-Based Medical History Sharing System

**MedTrack** is a full-stack web application that enables patients and healthcare professionals to securely store and share medical records using a custom blockchain built in JavaScript.

Built as part of a project at **VIT Bhopal University**, this system ensures privacy, immutability, and verifiability of medical data using blockchain technology.

---

## 🚀 Features

- ✅ Custom JavaScript Blockchain
- ✅ Node.js & Express.js Backend
- ✅ HTML/CSS/JavaScript Frontend
- ✅ REST APIs for Adding and Verifying Records
- ✅ SHA256-based Proof-of-Work
- ✅ Dockerized for Easy Deployment
- ✅ Tamper Detection and Chain Validation

---

## 📁 Project Structure

```

medtrack/
│
├── blockchain/           # Blockchain core logic (Block & Blockchain classes)
├── routes/               # Express.js API routes
├── public/               # Static frontend files (HTML/CSS/JS)
├── Dockerfile            # Docker configuration
├── server.js             # Main backend server
├── package.json
└── README.md

````

---

## 🛠️ Setup Instructions

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or above)
- [Docker](https://www.docker.com/) (optional, for containerized deployment)

---

### 🖥️ Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/medtrack.git
   cd medtrack
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   node server.js
   ```

4. **Open in browser**

   Navigate to: `http://localhost:3000`

---

## 📦 Docker Deployment (Optional)

1. **Build Docker image**

   ```bash
   docker build -t medtrack .
   ```

2. **Run the container**

   ```bash
   docker run -p 3000:3000 medtrack
   ```

3. Access the app at: `http://localhost:3000`

---

## 🔑 API Endpoints

| Method | Endpoint                 | Description                    |
| ------ | ------------------------ | ------------------------------ |
| POST   | `/addCertificate`        | Add a new medical record       |
| GET    | `/getBlockchain`         | Fetch the full blockchain      |
| GET    | `/verifyCertificate/:id` | Verify if a record is tampered |

---

## 🌐 Frontend Pages

* **Add Medical Record Page**: Submit patient data (e.g., Name, Condition, Date, Doctor)
* **Verify Record Page**: Verify data immutability using record ID

---

## 🧪 Testing & Validation

* ✅ Successfully mined and added blocks for each medical record
* ✅ Tamper detection invalidates altered chains
* ✅ Verified sequential and valid hash linkage
* ✅ Real-time verification responses from backend

---

## ⚙️ Technologies Used

* **Frontend**: HTML5, CSS3, JavaScript
* **Backend**: Node.js, Express.js
* **Blockchain**: Custom JavaScript Blockchain (SHA256, PoW)
* **Deployment**: Docker (Node Alpine)

---

## 📈 Future Enhancements

* Role-based login (Patients, Doctors, Hospitals)
* Persistent storage with MongoDB
* QR-based record sharing
* Upgrade to P2P blockchain network
* Smart contract integration for access control

---

## 👨‍💻 Author

**Utkarsh Singh**
BTech CSE, VIT Bhopal University

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ⭐️ Support

If you find this project helpful, give it a ⭐️ on GitHub to support continued development.

```

---

