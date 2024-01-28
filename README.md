#Mentor-Student Management API
The Mentor-Student  Management API simplifies mentor-student relationship administration with features for CRUD operations.

#Key API Endpoints

[!Create Mentor (POST)]
>Establish a new mentor profile.
>Endpoint: /mentor/createMentor

[!Create Student (POST)]
>Register a new student.
>Endpoint: /students/createStudent

[!Assign Student to Mentor (POST)] 
>Link a student to a mentor, fostering a learning relationship.
>Endpoint: /common/assign-mentor/:mentorName/:studentName

[!Change Mentor for Student (PUT)] 
>Assign a new mentor to a student or modify an existing mentor-student relationship.
>Endpoint: /common/change-mentor/:studentName/:newMentorName

[!Get All Students for a Mentor (GET)] 
>Retrieve a comprehensive list of all students under the guidance of a specific mentor.
>Endpoint: /mentors/getAllStudents/:mentorId

[!Get Previously Assigned Mentor for a Student (GET)] 
>Access the historical data of a student's previously assigned mentor.
>Endpoint: /students/getPreviousMentor/:studentId

[!Tip - Detailed DOcumentaion]
> https://documenter.getpostman.com/view/32504285/2s9YyqihQs




