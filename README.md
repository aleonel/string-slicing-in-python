# string-slicing-in-python

Author: Anthony L
October 2, 2021
This program will run and test all cases at once. Cases are contained in the examples string list.

Question:
Python Challenge

Your challenge is write a program to ask the user to enter their school username in the following format:
Year Group Using two digits (e.g. “07” for year 7, “11” for year 11, “00” for staff members)
1 character for their initial (first letter of their firstname)
The user’s lastname
A 2-digit code: “_S” for students, “_T” for teachers, “_A” for admin staff.
For instance the following usernames are valid usernames:

07jFox_S
09kJohnson_S
11rTaylor_S
00pJones_T
00jOliver_A
Your program should read the username and decide:

If the username is less than 6 characters long the program should ask the user to enter a valid username.
If the username does not contain the character “_” it should also ask the user to enter a valid username.
If the username is valid, the program should decide if the user is a member of staff or a student.
If they are a student the programme should find out their year group.
The program should also display the initial of the student as well as their lastame.
Finally the program should display whether the user is a Student, a Teacher or an Admin member of staff.

Example run:
#list
examples =["07jFox_S", "09kJohnson_S","a16", "11rTaylor_S", "00pJones_T", "00jOliver_A"]

#program output
Output:

Results for 07jFox_S:
Details: 
- Name: J. Fox 
- Role: Student 
- Year: 07

Results for 09kJohnson_S:
Details: 
- Name: K. Johnson 
- Role: Student 
- Year: 09

Results for a16:
- Invalid Username, check below
	- Error: Username is less than 6 characters
	- Error: Username invalid missing _.


Results for 11rTaylor_S:
Details: 
- Name: R. Taylor 
- Role: Student 
- Year: 11

Results for 00pJones_T:
Details: 
- Name: P. Jones 
- Role: Teacher 
- Year: 00

Results for 00jOliver_A:
Details: 
- Name: J. Oliver 
- Role: Admin 
- Year: 00

[Finished in 0.1s]
