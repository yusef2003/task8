PATIENT(*PatientID* , Name, Address, Age, Email, Phone, MedicareNumber, ***PrimaryDoctorID*** )



DOCTOR(*DoctorID* , Name, Email, Phone, Specialty, YearsExperience)



PHARMA\_COMPANY(*CompanyID* , Name, Address, Phone)



DRUG(*DrugID* PK, TradeName, Strength, ***CompanyID*** )



PRESCRIPTION(*PrescriptionID* , Date, Quantity, ***PatientID*** , ***DoctorID*** , ***DrugID*** )



