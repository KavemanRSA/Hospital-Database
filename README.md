# Hospital-Database

Hospital/Clinic Database Schema & Sample Data

Overview

	This project provides a relational database schema and sample data for a small hospital or clinic. It includes tables for 
    doctors, patients, specialities, appointments, allergies, and prescribed medications. The schema is designed to demonstrate 
    normalised database design, proper foreign key relationships, and realistic data population for educational purposes.
	
Features

	
	Tables & Relationships:

		SPECIALITY – Medical specialities offered by the hospital.
		DOCTOR – Doctors with their specialities and optional supervisors.
		PATIENT – Patient records, including contact info and assigned doctors.
		ALLERGY – Possible patient allergies.
		PATIENT_ALLERGY – Linking patients to allergies.
		APPOINTMENT – Appointment records including blood pressure, weight, and treatment notes.
		MEDICINE – Medicines prescribed by doctors.
		PATIENT_MEDICINE – Linking appointments to prescribed medicines.

	Data Integrity:

		- Primary and foreign key constraints ensure referential integrity.
		- Unique constraints prevent duplicate entries.
		- Sample data provides a realistic hospital scenario for practising queries.

License

	This project is licensed under the CC0 License. You are free to use, copy, modify, and distribute this project for educational or personal purposes.

Notes

	- All data (IDs, names, addresses) are fictional and for demonstration only.
	- Designed for learning SQL, database design, and query practice.
	- Works with most SQL-based database systems; some datatype adjustments may be required depending on the SQL engine.
