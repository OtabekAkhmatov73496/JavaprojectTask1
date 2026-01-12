Hi! This project is a special milestone for me. Created as 
part of the "Studia globalnych mozliwosci" program at 
Vistula University, it marks the beginning of my path 
into modern Java development.

-----------------------------------------------------------
 WHAT IS THIS PROJECT ABOUT?
-----------------------------------------------------------
I wanted to build something that bridges the gap between 
backend code and the web browser. This application is a 
dynamic "Greeting Service". 

It’s not just static text; it’s an interactive experience. 
You give the app a name, and it talks back to you through 
a clean web interface.

-----------------------------------------------------------
(HOW IT WORKS)
-----------------------------------------------------------
The magic happens through a few key components working 
together:

* THE BRAIN (HelloController.java): 
  This is the traffic controller. 
  It waits for someone to visit the "/greeting" web address 
  and captures the name you type in the URL.

* THE FACE (greetings.html): 
  Using Thymeleaf, I created a template that says hello 
 . It’s smart enough 
  to take the name from the controller and show it live 
  on the screen.

* THE ENGINE (FirstProjectJavaSpringApplication.java): 
  The main entry point that starts the entire Spring Boot 
  engine.

-----------------------------------------------------------
 TRY IT OUT YOURSELF!
-----------------------------------------------------------
Want to see it in action? Once the app is running, just 
open your browser and visit:

URL: http://localhost:8080/greeting?name=YourName

If you see "Hello Vistula [YourName]" on the screen, the 
connection is successful!

-----------------------------------------------------------
 UNIVERSITY ROOTS
-----------------------------------------------------------
This project was developed at:
Akademia Finansow i Biznesu Vistula
"Studia globalnych mozliwosci"

===========================================================
