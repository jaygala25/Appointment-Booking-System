# Appointment-Booking-System
It's a Desktop Application used by Attendant to book patient's appointment instead of maintaining paper-based databases.

The basic idea behind the project is, it lets attendant book patient's appointment for a particular doctor visiting hospital and backend does the necessary checking for slots and making entries in database.

This Project is made using Java, more specifically, Swing, JDBC and MySQL.

## Some advantages of computerized database over paper-based database

1. Very fast to find a specific record.
2. Can be used to analyse the data.
3. Can easily update or amend a record.
4. Records are stored safely, they are available when needed.
5. The database can be kept secure by use of passwords and many more....

## How does this project works ?

Consider each doctor can treat a maximum of 5 patients per day at a particular hospital and there are no appointments booked currently.

1. Select required medical field.

![select_field](https://user-images.githubusercontent.com/32769719/41970505-bf9790d6-7a28-11e8-8add-a132f2e3916d.JPG)

2. After selecting required field, say Cardiology, select the required doctor.

![select_doctor](https://user-images.githubusercontent.com/32769719/41972110-688523ca-7a2e-11e8-8047-c021cad58111.JPG)

3. After selecting the required doctor, the backend will check for the availability of slot in that doctor’s table in database. 

4. **Condition** - If the no. of entries of the current date is less than 5 then attendant will enter the required information and appointment will be booked successfully.

![booked](https://user-images.githubusercontent.com/32769719/41972443-8b324e10-7a2f-11e8-961d-741f952b0398.JPG)

5. Database table:

![half_database](https://user-images.githubusercontent.com/32769719/41972456-961065d8-7a2f-11e8-94a7-d976a0ac3e15.JPG)

6. If no. of entries of the current date becomes equal to 5 then appointment is not booked.

![not_booked](https://user-images.githubusercontent.com/32769719/41972471-9f27ffaa-7a2f-11e8-9e6e-7500b07e1afc.JPG)

7. Database table:

![full_database](https://user-images.githubusercontent.com/32769719/41972474-a431d250-7a2f-11e8-93a1-4384db16bb8c.JPG)
