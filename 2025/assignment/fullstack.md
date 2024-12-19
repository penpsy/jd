### **Full-stack Assignment: Building a Secure and Scalable Appointment Booking System with Healthcare Compliance**

**Objective:**
Design and implement a **secure appointment booking system** with integrated **patient forms**, **real-time scheduling**, and **medical record management**. The application must support **authentication**, **data validation**, and **HIPAA-compliant security** practices. Use modern technologies such as **Next.js/ModernJS**, **WebSockets**, **ORMs**, and **React** to develop a scalable and modular solution.

### **Deliverables:**

1. **Backend API (Next.js 15/ModernJS + WebSockets + ORM)**:
   - Build a **REST API** using **Next.js API routes** for handling:
     - **Appointment booking** (CRUD operations).
     - **Patient record management** (basic data models like name, medical history, and appointments).
     - **Secure user authentication** using **OAuth2** or **JWT**.
   - Implement **WebSockets** to support **real-time notifications** (e.g., appointment reminders).
   - Use an **ORM (Prisma/Sequelize/TypeORM/Drizzle)** for managing patient data and appointments in a **database**.
   - Implement **data validation** for all patient information and appointments (e.g., valid dates, consent forms).
   - Ensure **HIPAA compliance**: encrypt sensitive data at rest and in transit (use **AES-256** and **SSL/TLS**).

2. **Frontend (Next.js/ModernJS + React)**:
   - Build a **Next.js/ModernJS frontend** to display:
     - A **calendar view** for scheduling and viewing appointments.
     - Forms for **patient data entry** (name, medical history) and **appointment booking**.
     - **Real-time notifications** (e.g., appointment updates, reminders) using WebSockets.
   - Implement form handling with **React Hook Form** or **Formik**, ensuring **dynamic fields** for patient consent and medical history.
   - Ensure that the frontend supports **responsive design** (mobile-friendly).

3. **Data Security & Compliance**:
   - Implement **password hashing** for user authentication (e.g., using **bcrypt** etc.).
   - Ensure **encryption** of sensitive medical data at rest using **AES-256** and enforce **secure communication** over HTTPS including database access [DO NOT USE PLAINTEXT PROTOCOL].
   - Implement **role-based access control** for different types of users (e.g., patient, provider, admin).
   - Build a **logging and audit trail** for data changes (e.g., appointment creation, record modifications).

4. **Testing & Quality**:
   - Write **unit tests** for API routes using **Jest**.
   - Use **Cypress** or **Playwright** for **end-to-end testing** of the booking flow (appointment creation, patient record submission).
   - Ensure **100% test coverage** for business logic in the backend (appointment creation, user authentication).

5. **CI/CD**:
   - Set up a simple **CI/CD pipeline** using **GitHub Actions** to automatically build the backend and frontend to a container image.
   - Ensure the system is deployable and tests pass on every push.

### **Time Commitment:**
- **15 hours of focused work** by completing at least any **2 features** (split the work into backend and frontend tasks).

### **Assessment Criteria:**
- **Backend Architecture**: Clean, modular API with secure authentication and data validation.
- **Frontend Design**: Responsive and user-friendly UI for scheduling, patient forms, and notifications.
- **Security**: Proper encryption, secure authentication, and role-based access control.
- **Compliance**: Implementation of HIPAA-compliant security practices (data encryption, logging).
- **Testing & Quality**: High-quality code with adequate test coverage and automated CI/CD setup.
- **Version Control System**: Rich demonstration of best practices of using Git in the project evolution.

### **Technologies to Use**:
You are free to choose any stack/technology to implement these features

