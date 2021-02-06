# Clinic-Management-System
This is an C project to manage clinic easily

 ** **There's an two login system one for admin and the second one for user or clint

## Admin Mode:

The system asks for password, the default password is 1234. The system allows 3 trails for the password
entry, if the entered password was incorrect for 3 consecutive times, the system will close. After login
in the admin mode, the system will provide the following features:


- Can add new patient record.
add a new patient, the user shall admin shall enter these basic information: name, age, gender and
ID. The ID will be unique for the user, if the entered ID is already exists, the system will reject the
entry.


- Can edit patient record.
By entering patient ID the system will checks if the ID exists, the system will allow the user to edit the
patient information. If not, the system will display incorrect ID message.

- Can reserve a slot with the doctor.
By default there are 5 available slots, 2pm to 2:30pm, 2:30pm to 3pm, 3pm to 3:30pm, 4pm to 4:30pm
and 4:30pm to 5pm. Upon opening of this window, the system will display the available slots. The
admin shall enter the patient ID and the desired slot. The reserved slot will not appear again in the next
patient reservation.

- Can cancel reservation.
The admin can cancel a reservation by entering the patient ID. This reservation will be shown again in
the available slots window.


##  User Mode:
There is no password. The system allows the following features:

- View patient record.
By entering the patient ID, the system will show the basic information for the patient.

- View today’s reservations.
In this view, the system will print all reservations with the patient ID attached to each reservation slot.
