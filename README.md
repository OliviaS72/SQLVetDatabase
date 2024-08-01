## 8 table database created with invented data to ensure sound relationships among keys between the tables. This database models a veterinary clinic's patients and appointments. 
## There is an expertise table for the vet's field, a veterinarian table for vet's names, a species table for the animal patients,
## a treatment table, an insurance table, a petowner table, a patient table for the pet's names, and an appointment table. These tables
## are all filled with records for different details pertaining to the table's subject. For example, some fields within the veterinarian table are 
## VET_ID, VET_FNAME, VET_LNAME, and STATE_LICENSE, with the VET_ID being the primary key. For the insurance table, some of the fields are 
## POLICY_NO, POLICY_HOLDER_FNAME, POLICY_HOLDER_LNAME, INSURANCE_CO, and DEDUCTIBLE_DOLLARS, with POLICY_NO being the primary key.##

## I show an update query, an alter query, a query with a 'where' clause, a query with the 'like' operator, a query using ORDER BY, a query with an aggregate function,
## query with GROUP BY, GROUP BY/HAVING, and a calculated field. Also, I demonstrate a subquery with a SELECT statement to select records 
## for all patients who recieve treatment ending in 'therapy' by using a LIKE clause within the SELECT subquery.##

## I created a view to show appointments that occurred after December 1, 2022. Another view shows the full name, state of license, 
## and area of expertise for only verterinarians who earned their PhD from Auburn University.

## I created a stored procedure called 'InsertPetOwner' to add a new pet owner to the PETOWNER table whenever there is a new patient. 

## Another stored procedure I created was called 'UpdateVetInfo' to adjust the name of a vet, the state of his or her license,
## the school where they earned a PhD, years of experience, or area of expertise for any VET_ID. 

## The final stored procedure I created was called 'DeleteAppointment' to allow appointments meeting certain parameters to be deleted from the appointment table. 

## Since I created a stored procedure to delete appointments, I also created a trigger and a backup appointment table so that any deleted records from
## the appointment table got added to a backup table called APPOINTMENT_BACKUP.
