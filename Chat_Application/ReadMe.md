## Introduction
  This is a code repository of a real time chat application between a student and a tutor, where the student can get his/her queries answered from tutors who are experts. The chat application focuses on privacy and userfriendliness.

The frontend is built with React and the backend is handled by Node.js and socket.io.
For realtime bidirectional communication web socket library socket.io is used.

## Salient Features:
* A room will contain only a single student so the student can clear all his queries without any interference.
* Since there are multiple tutors the student doesnt have to wait.
* A tutor can not login as a student
* The conversations is sent to the database for future analysis


The student logins with his name and his mail. Authentication is done by google login.
![](Images/join.png)


After the student successfully logs in he is taken to the private room
![](Images/chat.png)

Login page for admin.
![](Images/adminLogin.png)

After the admin successfully logs in he is taken to the waiting room where the status of the student is shown. He/She can join the room of the student.   
![](Images/admin.png)


Tutor's chat window - After the tutor had joined. 
![](Images/chat2.png)

When multiple users are waiting in the waiting room
![](Images/admin2users.png)

scroll down feature
![](Images/chat3.png)

Chat window after the tutor had left.
![](Images/chat4.png)



