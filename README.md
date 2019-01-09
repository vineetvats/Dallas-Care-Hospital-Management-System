# Dallas-Care-Hospital-Management-System
Database Management System Implementation
Problem Description
Dallas Care is a hospital and medical care center. Dallas Care would like one relational
database to be able to smoothly carry out their work in an organized way. The hospital has
following modules: Person, Employee, Patient, Visitors, Pharmacy, Treatment, Rooms,
Records and Medical Bill Payment. A Person can be an Employee or a Class 1 Patient.
Details of a person such as Person ID, Name (First, Middle, Last), Address, Gender, Date of
Birth, and Phone number (one person can have more than one phone number) are
recorded. A person ID should be in the format, ‘PXXX’, where XXX can be a value between
100 and 999. A Class 1 patient is a person who visits the hospital just for a doctor
consultation. A person can be both an employee and a Class 1 patient. Employee is further
classified as Doctors, Nurses or Receptionists. The start date of the employee is recorded.
The specialization of the doctor is stored and doctors are further classified into Trainee,
Permanent or Visiting. Every Class 1 patient consults a doctor. A Class 1 patient can consult
at most one doctor but one doctor can be consulted by more than one Class 1 patient. A
Class 2 patient is a someone who is admitted into the hospital. A Class 2 patient can be an
Employee or a Class 1 Patient or both. A doctor attends Class 2 patients. One doctor can
attend many Class 2 patients but a Class 2 patient can be attended to by at most 2 doctors.
The date of patient being admitted into the hospital is recorded. A Visitor log is maintained
for the Class2 Patients, which stores information such as patient ID, visitor ID, visitor name,
visitor’s address, and visitor’s contact information. Pharmacy details such as Medicine code,
Name, Price, Quantity and Date of expiration is recorded. The database also stores the
information of the various kinds of treatments that are offered in the hospital. The treatment
details such as ID, name, duration and associated medicines are recorded. When a
treatment is assigned to a Class 2 patient, the treatment details, medicine details and patient
details are recorded so that the doctor can easily access this information. Nurses governs
rooms. Each nurse can govern more than one room, but each room has only one nurse
assigned to it. The room details such as room ID, room type and duration is recorded. Each
Class 2 patient is assigned a room on being admitted to the hospital. A records database is
maintained by the receptionist who keeps record of information such as record ID, patient ID,
date of visit, appointment and description. The receptionist also records the payment
information with the patient’s ID, date of payment and the total amount due. Payment is
further classified into Cash or Insurance. A person can pay by cash, or by insurance or pay
via a combination of both. The cash amount is recorded if a person pays by cash. For
Insurance, the insurance details such as Insurance ID, Insurance Provider, Insurance
coverage and the amount is recorded.
