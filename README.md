## OfficeOWL: A Security-First Workforce Management Platform
OfficeOWL is a comprehensive workforce management solution designed from the ground up with a primary focus on security and data integrity. In today's workplace, managing employee attendance, leave, and sensitive data requires more than just functional tools; it demands a system that can guarantee privacy and protect against unauthorized access. This project was created to address that need, providing a robust platform where organizations can manage employee activities with confidence, knowing that all information is handled securely and in compliance with data protection standards.

### Core Features & Functionality
The platform offers a complete suite of tools for effective workforce management, all accessible through a clean and intuitive user interface. The core features include a role-based leave and attendance system, where employees can submit requests and managers can approve them based on a clear permission hierarchy. The system also includes dynamic dashboards that provide users with at-a-glance summaries of their attendance records and leave balances. For administrative and HR purposes, OfficeQ features an automated PDF processing engine that generates encrypted reports, ensuring that sensitive data remains secure even when exported.

### A Deep Dive into Security
Security is not an afterthought in OfficeQ; it's the central pillar of its architecture. To safeguard all user data, the platform implements AES encryption, one of the most secure encryption standards, protecting information both at rest and in transit. User accounts are fortified with Two-Factor Authentication (2FA), adding a critical layer of defense against unauthorized logins. Furthermore, sensitive information is protected within the UI using data masking techniques, preventing full exposure of private data. To protect the platform from automated bots and spam, Google's reCAPTCHA is integrated into key user endpoints.

### Technical Stack
The application was built using a modern and reliable set of technologies to ensure both performance and security.

Frontend: React.js

Backend & Database: Firebase

API: RESTful API architecture

Security: AES encryption, Two-Factor Authentication (2FA), Google reCAPTCHA
