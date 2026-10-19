# Prog5121part2
My Java chat application, called ChatApp3, is designed to allow users to log in and send or manage messages. I divided my program into different classes to make my code easier to understand, organise and maintain. Each class has its own responsibility and helps the application perform its functions correctly.

In my ChatApp3.java class, I use the main() method to start my program. I use the Scanner class to allow users to enter information using the keyboard. I also import ThreadLocalRandom, which allows me to generate random values that can be used for message references or identifiers. This class controls the main flow of my application and connects the different parts of my program.

In my Login.java class, I handle the login process. The user enters their username and password, and the program checks whether the login details are valid according to the conditions I have implemented. If the details are correct, the program displays a success message. If they are incorrect, it displays an appropriate message. This helps me manage user access to my chat application.

In my MessageManager.java class, I manage the messages in my application. This class can be used to store, retrieve and organise messages, depending on the methods I have implemented. I separated this functionality from my main class to keep my code organised and make it easier to manage message-related operations.

In my MessageTest.java class, I test the message functionality to check whether it works as expected. I use testing to identify possible errors and make sure that the message-related methods produce the correct results. This helps me check my code and fix problems that may occur during the development of my application.

In conclusion, I used different classes to make my Java chat application more organised and easier to maintain. The ChatApp3.java class starts my program, the Login.java class handles user login, the MessageManager.java class manages messages, and the MessageTest.java class tests the message functionality. By separating these tasks, I can understand my code better and make changes to individual parts without having to rewrite the entire application.
