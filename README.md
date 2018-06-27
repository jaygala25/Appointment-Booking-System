# Appointment-Booking-System
It's a software solution used by attendant to book patient's appointment instead of maintaining paper-based databases.

The basic idea behind the project is, it lets attendant book patient's appointment for a particular doctor visiting hospital and backend does the necessary checking for slots and making entries in database.

This Project is made using Java, more specifically, Swing, JDBC and MySQL.

## How the project works ?

Consider each doctor can treat a maximum of 5 people per day at a particular hospital.

1. Select required medical field.

![select_field](https://user-images.githubusercontent.com/32769719/41970505-bf9790d6-7a28-11e8-8add-a132f2e3916d.JPG)

2. After selecting required field, say Cardiology, select the required doctor.

![select_doctor](https://user-images.githubusercontent.com/32769719/41972110-688523ca-7a2e-11e8-8047-c021cad58111.JPG)

3. After selecting the required doctor, the backend will check for the availability of slot in that doctor’s table in database. 

4. **Condition** - If the no. of entries of the current date is less than 5 then attendant will enter the required information and appointment will be booked successfully.

