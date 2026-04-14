# 🔐 Enterprise PKI Lab using EJBCA

## 🚀 Overview
This project demonstrates a hands-on implementation of a Public Key Infrastructure (PKI) using EJBCA running in Docker.

It simulates real-world enterprise certificate management workflows including identity creation, certificate issuance, and certificate-based authentication.

---

## 🧰 Technologies Used
- EJBCA (PKI platform)
- Docker
- Mozilla Firefox (certificate management)
- Public Key Infrastructure (PKI)

---

## 🏗️ Architecture
- Docker container hosting EJBCA
- Internal Certificate Authority (ManagementCA)
- Browser-based certificate authentication

---

## 🔧 Setup Highlights
- Deployed EJBCA using Docker
- Generated SuperAdmin certificate
- Configured Certificate Profiles and End Entity Profiles
- Created users and issued certificates

---

## 🔐 Certificate Workflow
1. Create Certificate Profile  
2. Create End Entity Profile  
3. Register user (end entity)  
4. Enroll certificate  
5. Import certificate into browser  

---

## 📸 Screenshots

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### Certificate Profile
![Certificate Profile](screenshots/certificate-profile.png)

### End Entity Profile
![End Entity Profile](screenshots/end-entity-profile.png)

### Add User
![Add User](screenshots/add-user.png)

### Enrollment
![Enrollment](screenshots/enrollment.png)

### Certificate Download
![Certificate Download](screenshots/certificate-download.png)

---

## 🧠 Key Skills Demonstrated
- PKI architecture and design  
- Certificate Authority (CA) configuration  
- Identity and access management  
- Certificate lifecycle management  
- Client certificate authentication (mTLS)

---

## 🚀 Future Enhancements
- Subordinate CA hierarchy  
- Certificate revocation (CRL/OCSP)  
- Kubernetes integration  
- Automated certificate issuance via API  

---

## 👩‍💻 Author
Colleen Cummings
