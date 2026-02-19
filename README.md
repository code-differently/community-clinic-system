# Community Clinic System


You are building a console-based system for a small community clinic.

The clinic needs help managing:

* Patients
* Check-ins
* Appointments
* Daily reports

Your job is to design and build the system step-by-step.

---

# Skills Being Tested

This project will assess your understanding of:

* Variables
* Methods
* Loops
* Conditionals
* Arrays
* ArrayList
* Objects and Classes

You must demonstrate clean structure and logical thinking.

---

# Required Files

Create the following classes:

* `YourNamePatient.java`
* `YourNameAppointment.java`
* `YourNameClinicSystem.java`
* `YourNameClinicApp.java` (Main class)

You may add additional helper methods if needed.

---

# Tier 1 — Patient Management

Build the foundation.

Your system must allow the user to:

1. Add a new patient
2. View all patients
3. Check in a patient
4. Search for a patient
5. Exit

Requirements:

* Store patients using an `ArrayList`
* Assign each patient a unique ID
* Use methods (no large main method)
* Use loops for searching and listing
* Use conditionals for validation

---

# Tier 2 — Appointment Scheduling

Now the clinic needs scheduling.

Add:

* An array representing daily time slots
* Ability to schedule appointments
* Ability to cancel appointments
* View the full schedule

Requirements:

* Prevent double-booking a time slot
* Validate input
* Store appointments using an `ArrayList`

---

# Tier 3 — Clinic Business Rules

Make it realistic.

Add:

* Daily summary report
* Appointment completion tracking
* Rules that prevent invalid actions
* Basic waitlist feature

Your system should now behave like a small real clinic system.

---

# Creative Extension (Choose ONE)

Choose **one** of the following stretch challenges to extend your project.
This is your opportunity to show deeper understanding and creativity.

1. **Priority Patients**
   Add a priority level (Emergency, Regular, Follow-up) and adjust scheduling behavior.

2. **Multiple Doctors**
   Add a Doctor class and assign appointments to specific doctors.

3. **File Saving (Persistence)**
   Save patient and appointment data to a text file and reload it when the program starts.

4. **Search Filters**
   Allow searching patients by phone number or appointment status.

5. **Improved Reporting**
   Add more detailed daily statistics (e.g., busiest hour, total cancellations).

6. **Rescheduling Feature**
   Allow appointments to be moved to a different time slot safely.

7. **Patient Visit History**
   Track and display a patient’s previous completed appointments.

8. **Billing Simulation**
   Add cost tracking and print a simple receipt.

9. **Input Validation System**
   Create a reusable validation method for all user inputs.

10. **Console UI Upgrade**
    Improve the user interface with formatted menus and clearer output layout.

You may choose more than one once you finish early.

Required Personalization Component:

To reduce identical solutions:
Each student must choose ONE of the following themes and rename their system accordingly:

* Dental Office
* Auto Repair Shop
* Gym Check-In
* Barber Shop
* University Advising Office
* Tech Support Desk
* Event Ticketing Desk
* Coffee Shop Pickup System
* Vet Clinic
* DMV Service Counter

---

# Expectations

* Clean class design
* Logical method structure
* Proper use of loops and conditionals
* Meaningful variable names
* Organized code
* Create your own branch
* Make at least 10 commits

---

# Do NOT

* Put everything in `main`
* Hardcode answers
* Overcomplicate your design

---

# Submission

Submit:

* All `.java` files
* Code that runs without errors
* Clear console interaction

---

Build it like a real system.

========================================
     WILMINGTON COMMUNITY CLINIC
========================================

1. Add New Patient
2. View All Patients
3. Check In Patient
4. Search Patient
5. Schedule Appointment
6. Cancel Appointment
7. View Daily Schedule
8. Complete Appointment
9. Daily Report
0. Exit

Enter choice: 1
----------------------------------------
Enter patient name: Marcus Hill
Enter phone number: 302-555-8912

Patient added successfully.
Assigned ID: 1
----------------------------------------

Enter choice: 1
----------------------------------------
Enter patient name: Jasmine Lee
Enter phone number: 302-555-1133

Patient added successfully.
Assigned ID: 2
----------------------------------------

Enter choice: 2
----------------------------------------
PATIENT LIST
----------------------------------------
ID: 1 | Marcus Hill | Checked In: false
ID: 2 | Jasmine Lee | Checked In: false
----------------------------------------

Enter choice: 3
----------------------------------------
Enter patient ID to check in: 1

Marcus Hill is now checked in.
----------------------------------------

Enter choice: 5
----------------------------------------
Enter patient ID: 1
Enter time slot (0–7): 3
Enter reason: Physical Exam

Appointment scheduled successfully.
----------------------------------------

Enter choice: 5
----------------------------------------
Enter patient ID: 2
Enter time slot (0–7): 3

Error: Time slot already booked.
----------------------------------------

Enter choice: 7
----------------------------------------
DAILY SCHEDULE
----------------------------------------
Slot 0: Available
Slot 1: Available
Slot 2: Available
Slot 3: Marcus Hill | Physical Exam | SCHEDULED
Slot 4: Available
Slot 5: Available
Slot 6: Available
Slot 7: Available
----------------------------------------

Enter choice: 8
----------------------------------------
Enter time slot to complete: 3

Appointment marked as COMPLETED.
----------------------------------------

Enter choice: 9
----------------------------------------
DAILY SUMMARY REPORT
----------------------------------------
Total Patients: 2
Checked In: 1
Scheduled Appointments: 0
Completed Appointments: 1
Cancelled Appointments: 0
Open Time Slots: 7
----------------------------------------

Enter choice: 0

Thank you for using Wilmington Community Clinic System.
System shutting down...


