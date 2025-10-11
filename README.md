# Hi! I'm Igor De Castro!

Professional and results-driven Front-End and Mobile Developer with solid experience in building responsive, high-performance, and user-centric applications. Proficient in HTML, CSS, JavaScript, TypeScript, and experienced with modern frameworks such as React, Angular, and Vue. Skilled in mobile development using React Native, Flutter, and Kotlin, delivering robust and scalable cross-platform solutions. Focused on clean architecture, maintainability, and continuous improvement. Recognized for strong collaboration, effective communication, and a proactive approach to solving complex challenges in dynamic environments.

- 📫 Contact me via email: igordc38@gmail.com

## Technologies:
- React / Native
- Angular
- Vue
- JavaScript
- TypeScript
- Java
- Kotlin
- Flutter / Dart
- Redux
- Cypress (e2e)
- Jest (UnitTesting)
- Appium (e2e)
- RESTful APIs
- tailwind
- Refresh Token
- Axios (with interceptors)

## Architecture Concepts:
## 🧩 Front-end Layered Architecture

The front-end architecture follows a **modular and flexible design**, which may vary slightly depending on the project.  
However, it adheres to a consistent structural pattern that emphasizes **scalability**, **reusability**, and **maintainability** through clear separation of concerns across layers.

---

### 🖼️ View Layer

The **View layer** is subdivided into specific parts to ensure clear separation between presentation, logic, and styling:

- **Component** → Responsible exclusively for the visual structure (markup).  
- **Base** → Injects properties and controllers into the component.  
- **Controller** → Holds the state and actions of the screen. It is injected into the View and acts as a bridge between services and the visual layer.  
- **Style** → Contains the styling definitions for the page or component, ensuring design consistency.  
- **Types** → Centralizes all type definitions used by the controller to maintain strong typing and predictability.

---

### 🧠 Utils Layer

The **Utils layer** contains reusable helper functions and general-purpose utilities used throughout the system — essentially acting as code extensions.

**Examples:**
- Data formatters  
- Validators  
- Error handlers  
- Converters  

---

### ⚙️ Config / Lib Layer

The **Config/Lib layer** is responsible for initializing and configuring external libraries and dependencies, such as:

- HTTP clients (e.g., **Axios**)  
- File system utilities (**FS**)  
- Local or persistent storage  
- External integrations and infrastructure middleware  

---

### 💼 Business Layer

The **Business layer** organizes business logic and data communication between the front-end and back-end, structured into the following modules:

- **Services** → Handle operations that directly interact with View controllers, performing business logic or indirect API calls.  
- **Gateway** → Serves as an intermediary between the Services and the API, abstracting HTTP requests and endpoint management.  
- **Enum** → Contains system-wide constants and enumerations.  
- **Models** → Define API request and response models, representing entities handled by the gateways.

---

### 🔁 Data Flow

The standard data flow across layers follows this sequence:

Gateway → Service → Controller → Base → Component


**Flow Description:**
- **Gateway** → Communicates directly with the API.  
- **Service** → Handles business logic and orchestrates calls to the Gateway.  
- **Controller** → Receives data from the Service, processes it, and prepares it for rendering.  
- **Base** → Injects the controller instance into the component.  
- **Component** → Renders the processed data in the user interface.  

---




## Contact:
- Email: igordc38@gmail.com
- LinkedIn: [Igor De Castro Abrahao](https://www.linkedin.com/in/igor-de-castro-abrahao-324990207/)
