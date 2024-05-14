# Python with Django 

# Installation
To run this application, have the following Python libraries installed:

- Django
- Django Rest Framework
- ReportLab
- Requests

Install these libraries using pip:
- pip install django djangorestframework reportlab requests

# Django-Python workshop statement
Workshop Summary: Clinic Information Management Application

This workshop focuses on the functioning and responsibilities of the different roles within a clinic in relation to an information management application. The main objective of the application is to facilitate the efficient management of data related to patients, staff and administrative processes.

# Role Description:

- Human Resources: responsible for the administration of users, permissions and personnel data. In addition, they manage new employee information, ensuring that specific requirements are met in personal data and secure password creation. They do not have access to patient, medication or procedure information.

- Administrative Staff: Responsible for patient registration, appointment scheduling, billing management and insurance data. Maintain detailed patient information, including personal, contact, emergency and insurance information. Generate invoices with details of diagnoses, treatments and costs.

- Information Support: Responsible for maintaining data integrity in the application and providing technical assistance to users in case of access problems or queries related to information management.

- Nurses: Record vital patient data, medications administered, tests performed and relevant observations during care. They can schedule reminders for future visits.

- Physicians: Have full access to patient information and are responsible for maintaining detailed medical records. They record diagnoses, treatments, prescriptions and test results. The medical record is stored in an unstructured form in a NoSQL database, with each patient identified by ID card and date of care.

# Highlights:

The application handles sensitive patient and employee data, with strict protocols to protect privacy and security.
Specific rules are followed for creating and updating medical records, including diagnoses, treatments, and procedures.
The application differentiates between order types, such as medications and procedures, and stores this information in a structured way in an SQL database.
Additional rules are established for the association of multiple medications or procedures to a single order, as well as for specific cases such as hospitalization and nursing visits.

This summary provides an overview of the functionality and responsibilities of each role within the clinic information management application.

# Usage
Login data

- Doctor:
  
   - Username: wiliam_osler
   - Password: E=i4P&55uN&2
 
 - Nurse:
  
   - Username: jennifer_lawrence
   - Password: KQ73}Or48mC@

- Human Resources (RRHH):
  
   - Username: scarlett_johansson
   - Password: wE6h\Cw55`Kg
 
- Administrative Staff (PPAA):
  
   - Username: canco_rodriguez
   - Password: L#y$]2v9D83£
 
- Information Support (SSII):
   - Username: laura_escanes
   - Password: y248(yNi7&61
