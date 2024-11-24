<p align="center">
  <img src="hstu_logo_.png" alt="hstu_logo_.png" width="250" height="300">
</p>
<h1 align="center">
  <b>Blood Bank Manageent System</b>
</h1>
<h3 align="center">
  <br>
  <b>Level-3 Semester-I Project Report</b>  
</h3>
<h3 align="center">
  Course Code: CSE 305 
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>
<br>
<h3 align="center">
  Submitted by 
</h3>
<h3 align="center">
<b>Moniruzzaman Porag (ID: 2102044) </b> </h3>
<br>

<h3 align="center">
  Submitted To 
</h3>

<h3 align="center"><b>Pankaj Bhowmik  </b></h3>
<h3 align="center"><b>Lecturer, Department of CSE</b></h3>
<br>
<h3 align="center"> <b>Department of Computer Science and Engineering </b></h3>
<h3 align="center"><b>Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200</b></h3>

  ---

## Table of Contents  

1. [Abstract](#abstract)  
2. [Introduction](#1-introduction)  
3. [SDLC Phases](#2-sdlc-phases)  
   - [Planning](#21-planning)  
   - [Requirements Analysis](#22-requirements-analysis)  
   - [System Design](#23-system-design)  
   - [Implementation](#24-implementation)  
   - [Testing](#25-testing)  
4. [Challenges and Solutions](#3-challenges-and-solutions)  
5. [Conclusion](#4-conclusion)  
6. [References](#references)  

---

## Abstract  
The Blood Bank Management System (BBMS) is a software solution designed to automate and streamline blood bank operations. It bridges the gap between blood donors, recipients, and administrators through efficient management of blood stocks, donor databases, and blood requests. The project introduces advanced features to enhance reliability, scalability, and accessibility, ensuring timely delivery of critical resources during emergencies.  

---

## 1. Introduction  
The Blood Bank Management System (BBMS) is a software application designed to streamline blood donation and distribution processes. It ensures efficient management of blood inventories, donor information, and recipient requests. The development of this project follows the Software Development Life Cycle (SDLC), ensuring a structured approach for analysis, design, development, testing, and deployment.  

---

## 2. SDLC Phases  

### 2.1. Planning  
The planning phase focused on defining the objectives and scope of the BBMS project. The primary goals included:  
- Addressing inefficiencies in manual blood bank operations.  
- Providing an automated platform for donor and recipient management.  
- Enabling seamless tracking of blood inventories.  

**Key Deliverables:**  
- Project requirements document  
- Timeline and resource allocation  

### 2.2. Requirements Analysis  
In this phase, detailed functional and non-functional requirements were gathered. Inputs were collected through research, interviews with healthcare professionals, and analysis of existing systems.  

**Functional Requirements:**  
- User registration for donors and administrators.  
- Blood inventory management by blood group and expiry date.  
- Request and allocation management for recipients.  

**Non-Functional Requirements:**  
- The system should be responsive and user-friendly.  
- Data should be accurate and secure.  

### 2.3. System Design  
A comprehensive system design was created to meet the specified requirements.  

**High-Level Design (HLD):**  
- **Architecture:** A client-server model using JavaFX for the GUI and Java for business logic.  
- **Modules:**  
  - Donor Management  
  - Blood Stock Management  
  - Recipient Management  
  - Reports and Alerts  

**Low-Level Design (LLD):**  
- GUI wireframes for user interactions.  
- Class diagrams for representing entities (e.g., Donor, Blood-stock, Recipient).  
- Sequence diagrams for processes like blood donation and allocation.

  
![UML](https://github.com/user-attachments/assets/1d856fbc-150f-4c9f-a60e-57be08108064)


### 2.4. Implementation  
The system was developed in modular stages.  

**Tools and Technologies Used:**  
- **Programming Language:** Java  
- **GUI Framework:** JavaFX  
- **IDE:** IntelliJ IDEA  
- **Data Storage:** Local file system  

**Features Developed:**  
- Donor registration and search functionality.  
- Blood stock tracking with categorization.  
- Recipient request and allocation processing.  
- Alert system for low stock and expired units.  

### 2.5. Testing  
The testing phase ensured the system's reliability, accuracy, and usability.  

**Types of Testing Performed:**  
- **Unit Testing:** Validated individual modules like donor management and stock tracking.  
- **Integration Testing:** Tested interactions between modules.  
- **System Testing:** Ensured functionality across scenarios.  
- **User Acceptance Testing (UAT):** Feedback from users confirmed usability.  

---

## 3. Challenges and Solutions  

### Data Accuracy and Consistency  
**Challenge:** Ensuring accurate and up-to-date data for donors, blood stocks, and recipients.  
**Solution:**  
- Implement real-time data synchronization.  
- Use robust input validation.  
- Regularly update and audit data through automated checks.  

### Handling Low Stock Scenarios  
**Challenge:** Maintaining sufficient blood inventory during emergencies.  
**Solution:**  
- Set up alerts for low stock.  
- Create priority lists for specific blood groups.  
- Integrate with nearby blood banks.  

### Security of Sensitive Information  
**Challenge:** Protecting sensitive data like donor contact information and medical history.  
**Solution:**  
- Use role-based access control (RBAC).  
- Encrypt sensitive data.  
- Conduct regular security audits.  

---

## 4. Conclusion  
The Blood Bank Management System is a robust and efficient solution for automating blood bank operations. Following the SDLC framework ensured a systematic approach to development, minimizing errors and ensuring a high-quality product. This project demonstrates the potential for software solutions to significantly enhance healthcare processes, ultimately saving lives through improved blood management.  

---

## References  
- Java-FX Official Documentation  
- Research Papers on Blood Management Systems  
- Tutorials on Java and SDLC Methodology  
