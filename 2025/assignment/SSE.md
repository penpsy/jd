### **SSE Assignment: Scaffold an Enterprise-Grade Monorepo for Scalable Healthcare System**

**Objective**:  
Design and scaffold a **monorepo** architecture for a healthcare platform, leveraging modern tools and techniques to support **microservices**, **cross-platform code sharing**, and **modular frontend** development. Focus on scalability, maintainability, and efficient code organization.

---

### **Requirements**:

1. **Monorepo Setup**:
   - Use **Nx** or **Turborepo** to set up a **monorepo** with these directories:
     - `apps/` (web, mobile, electron apps)
     - `libs/` (shared components, utilities, models)
     - `services/` (backend services like `auth-service`, `appointment-service`)
   - Enable **code sharing** across frontend, backend, and mobile using **shared libraries** (e.g., API models, authentication).

2. **Microservices Architecture**:
   - Scaffold a simple **backend API** using **API routes**.
   - Implement **OAuth2/JWT authentication** in a central **auth-service**, use of any library is allowed.
   - Create a **CRUD API** template - reusable and extensible.
   - Use an **ORM** (e.g., **Prisma** or **Sequelize**) for data management.

3. **Frontend Setup**:
   - Scaffold a **JS frontend** to interact with backend services.
   - Implement **module federation** for dynamic loading of frontend components (e.g., `Module1`, `Module2`).
   - Create a **dynamically user creatable form** for data input.

4. **Mobile App**:
   - Scaffold a basic **React Native** or **Expo** app.
   - Reuse **shared logic/components** from the web frontend (e.g., authentication, form handling).

5. **CI/CD Pipeline**:
   - Set up **GitHub Actions** for building and testing, both backend and frontend apps.
   - Configure caching to optimize build and deploy times across services.

6. **Testing**:
   - Write **unit tests** for backend APIs using **Jest**.
   - Use **Cypress** or **Playwright** for **end-to-end testing** of the frontend flow.
   - Ensure **>95% test coverage** for core business logic, with report generation.

---

### **Deliverables**:
1. **Monorepo Structure**:
   - Organized codebase with clearly separated backend, frontend, mobile, and shared code.

2. **Backend Microservices**:
   - Scaffolded **auth-service**, and one stubbed sample CRUD service.
   - Secure API endpoints with **OAuth2/JWT**.

3. **Frontend & Mobile**:
   - JS frontend with **module federation**.
   - Scaffolded mobile app with reusable logic/components.

4. **CI/CD**:
   - Automated build and test pipeline using **GitHub Actions**.
   - Caching mechanism to optimize builds.

5. **Testing**:
   - Unit tests for backend services.
   - E2E tests for frontend flows.

---

### **Evaluation Criteria**:
- **Monorepo Architecture**: Scalability and modularity in app and service organization.
- **Code Sharing**: Efficient reuse of components and logic across frontend, backend, and mobile.
- **Microservices**: Clean, maintainable APIs with proper authentication.
- **Module Federation**: Successful integration of independent frontend modules.
- **CI/CD**: Efficient and automated deployment pipeline.
- **Testing**: Robust test coverage and reliable test automation.
- **Version Control System**: Rich demonstration of best practices of using Git in the project evolution.

---

### **Time Commitment**:
- **15 hours**

### **Tools & Technologies**:
You are free to choose any stack/technology to implement these features including selection and configuration & choice of the datastore. If choosing a JS environment, it should be a strongly typed project.
