# 🏫 Nursery Management System (NMS) - System Analysis & Design

This repository contains a complete System Analysis and Design documentation for a proposed Nursery Management System (NMS). This project was developed collaboratively as part of the "System Analysis and Design (CIS2303)" course to address the inefficiencies of manual nursery management by designing a centralized, user-friendly, and secure digital platform.

## 🚀 Project Overview & Problem Statement

Due to the lack of a proper system, daily nursery tasks—such as admissions, reporting, and transportation—take longer than they should. The NMS is designed to streamline these processes, offering a friendly interface for ease of use (especially for older users). 

**Key Objectives:**
*   Accelerate the admission and enrollment process.
*   Enhance swift communication between parents and teachers via daily activity and meal reports.
*   Automate transportation logistics and driver notifications.
*   Ensure data security, scalability, and legal compliance.

## 🔄 Adopted Methodology: Agile

We adopted the **Agile Methodology** for this project. Given that some requirements were dynamic, Agile allowed us to iterate through development cycles, refine features based on stakeholder feedback, and reduce the overall expected development time by half.

## 📊 Feasibility Study

A comprehensive feasibility study was conducted to ensure the project's success and stability:

*   **Technical:** Cloud-based infrastructure (AWS/Azure/Google Cloud) for scalability, paired with a secure database and strong network architecture.
*   **Operational:** Automated workflows for admission managers, a parent portal for tracking and scheduling, and automated alerts for drivers.
*   **Legal:** Strict compliance with data protection laws including FERPA, COPPA, GDPR, and HIPAA (for health data), ensuring child protection and digital security.
*   **Economic:** A realistic budget was formulated covering all development and maintenance phases.

| Component | Estimated Cost (USD) |
| :--- | :--- |
| Hosting | $20,000 - $50,000 |
| Personnel (Developers, PMs, QA) | $87,000 - $145,000 |
| Workstation & Hardware | $3,000 - $8,000 |
| Staff Training & Maintenance | $6,000 - $13,000 |
| **Total Estimated Budget** | **$120,000 - $220,000** |

## 📋 System Requirements

Requirements were gathered using surveys, yielding positive feedback and actionable suggestions (e.g., tighter security and simpler UI for older demographics).

**Functional Requirements:**
*   Online admission requests and fee processing.
*   Daily activity and meal report uploads by teachers.
*   Parent-teacher appointment scheduling.
*   Automated transportation allocation and driver notifications.

**Non-Functional Requirements:**
*   High-level security and authorization for student records.
*   Intuitive and accessible user interface.
*   High reliability, performance, and system scalability.

---

## 🏗️ Software Architecture (MVC)

The system is designed using the **Model-View-Controller (MVC)** architectural style. This separation of concerns ensures system stability, flexibility, and easier debugging.
*   **Model:** Divided into distinct packages (e.g., Enrollment Process, Appointment Scheduling) to avoid circular dependencies.
*   **View:** A Graphical User Interface (GUI) tailored for different users (Parents, Teachers, Managers) without altering the underlying logic.

**Full High-Level Architectural Model**

![High-Level Architectural Model](https://github.com/user-attachments/assets/514e0473-7ff8-4bb7-9655-b74782b27c0b )


---

## 📐 UML Diagrams & System Modeling

To visualize the system's behavior and structure, we developed several UML diagrams.

**Activity Diagram & To-Be System Perimeter**

![Activity Diagram](https://github.com/user-attachments/assets/c18bdc57-d7a3-4f67-aa41-13b77f4e7222 )

**Full Domain Class Diagram**
*Illustrates the relationships between Students, Admission Managers, Teachers, Parents, and Drivers.*

![Full Domain Class Diagram](https://github.com/user-attachments/assets/d6759119-cc28-487b-a468-cde4e8f29c05 )


---

## 🏃‍♂️ Sprint 1 Highlight: Request Enrollment

To demonstrate our Agile iterative process, below is the system modeling for our core sprint: **The Enrollment Process**.

*   **Primary Actors:** Parent, Admission Manager.
*   **Summary:** A parent submits an admission request. The manager reviews it based on age and seat availability. Upon acceptance, the parent pays the fee and is notified of successful enrollment.
**Use Case Diagram (Sprint 1)**

![Use Case Diagram - Sprint 1](https://github.com/user-attachments/assets/f7ccdbb3-11cf-451b-861e-c82a8ff83df4 )
  
**System Sequence Diagram (Sprint 1)**

![System Sequence Diagram - Sprint 1](https://github.com/user-attachments/assets/2223c223-de36-4649-a3f2-f403d17f9ff8 )

**Fragment of the Domain Class Diagram (Sprint 1)**

![Fragment Class Diagram - Sprint 1](https://github.com/user-attachments/assets/726b3bcc-d4e3-43ee-9a5c-75d5c2c1b174 )

---

## 💡 Conclusion & Impact

Investing in the Nursery Management System is essential in today's digital environment. By transitioning from manual procedures to an automated, Agile-driven platform, the NMS boosts operational output, guarantees data security, and fosters seamless communication among all stakeholders.

## 📄 Full Project Documentation

For an in-depth look at all sprints, complete feasibility studies, and detailed system models, please refer to the full project report:
* [View System Analysis & Design Report (PDF)](Nursery-Management-System-Report.docx/Nursery-Management-System-Report.pdf)
