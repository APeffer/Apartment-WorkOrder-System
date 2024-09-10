This software was created for Alex Peffer's Object Oriented Programming course at Texas State.

Description:
The purpose of this software is for apartment complexes to be able to create and manage work requests. This was my first program using a non-web-browser GUI.
The assignment had 2 parts. Part 1 was the software, part 2 was adding a GUI. 
The original program had more logic that had to be scrapped so I could have a working program by the due date for the assignment.
The GUI was made with Java AWT and Swing, and the program is written entirely in Java.

Use:
    The entry point of the program is MainFrame.java

A small GUI will display, in the top left you can choose your login type.

Start with the tenant!

![login](https://github.com/user-attachments/assets/419c16cf-6af9-4502-86b3-e9a61a81dd49)

The tenants are "Bob", "Alex, or "Jelly", enter a name to log in.

From this screen the tenant will be able to see their active work requests. Currently there is no database so requests are only active as long as the program is alive.
select a part that you need maintenance for. "Light bulb", "air filter", or "paint", and select create. You might want to make a few to experience the full program functionality.
Be aware: the work orders will not populate on the screen until you "log out" or close the tenant window and log back in again.

Now you can add work requests from another tenant, or go to the Boss login.

The boss login name is "Admin"
After logging in with the boss you can see all the work requests and data about the tenant, request, date, work request number, status, etc.

![Boss GUI](https://github.com/user-attachments/assets/c47c574d-ac5c-4e58-a918-605863cb0a71)

From here the boss/maintenance manager will be able to assign the work requests to an employee.
At the bottom of the screen, select a request number, assign a priority, and choose an employee to assign the request to.
AGAIN, the screen will not populate or change until you logout/login but you may still assign a few requests.

Now you can login as the employees "Jeff" or "Steve".
You will be presented with a gui showing the work requests assigned for that employee.

![employee gui](https://github.com/user-attachments/assets/a5249ce3-cbe1-4716-a956-d1604359e909)

From here the employee can choose a work order, after clicking "Work" the status of the work order will be changed from "Open" to "Closed".
This will be reflected in the Boss's account and the tenant's account.

![tenant gui 2](https://github.com/user-attachments/assets/dbc655b0-521f-4308-ab76-b81a9a9fc26a)
