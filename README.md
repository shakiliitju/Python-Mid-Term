
# Star Cinema 

1.	Make a class named Star_Cinema which will have one class attribute named hall_list which is an empty list initially. Make a method named entry_hall() to insert an object of class Hall (Described below) inside its hall_list.
2.	Make a class named Hall which will have 5 instance attributes given below	<br>
a.	seats which is a dictionary of seats information	<br>
b.	show_list which is an list of tuples	<br>
c.	rows which is the row of the seats in that hall	<br>
d.	cols which is the column of the seats in that hall	<br>
e.	hall_no which is the unique no. of that hall	<br>
Initialize an object of class Hall with rows, cols and hall_no. And insert that object to the Star_Cinema class attribute named hall_list inside the initializer using inheritance. seats and show_list will be empty initially.

4.	Make a method in Hall class named entry_show() which will take id, movie_name and time in string format. Make a tuple with all of the information and append it to the show_list attribute. Allocate seats with rows and cols using 2d list, initially all seats will be free. Make a key with id to the attribute seats and value will be the 2d list.

5.	Make a method in Hall class named book_seats() which will take an id of the show and list of tuples where every tuple contains the row and col of the seat. You need to check the id of the show, and book the seats. 	

6.	Make a method in Hall class named view_show_list() which will view all the shows running.	

7.	Make a method in Hall class named view_available_seats() which will take an id of show, and view the seats that are available in that show		

8.	Make a replica system so that the counter can view all shows that are running, view available seats in a show and can book tickets in a show.

9.	You need to handle the errors, for example-				<br>
a.	If someone gives a wrong id of a show	<br>
b.	If someone tries to book a seat that is invalid	<br>
c.	If someone tries to book a seat that is already booked

10.	Make the information of the classes as protected/private as you can so that the attributes can’t be accessed outside the class.				

