# Face Recognition Attandence System  | AGH Software Studio Project
*  By: Edibe Tutku Gayda, Eunseo Ko, Małgorzata Kuczera
## Project Description 
* Facial Detection and Facial Recognition are computer technologies used to detect human faces in a digital image or video and identify or confirm a person's identity using 
their face respectively. Today, these technologies are widely used. Such as face unlock used on smartphones and face detection in temperature scanner which was widespread 
during the Covid-19 pandemic.
* Using facial recognition technology, we decided to create a web application for the attendance system that can be used by educational Institutions, offices, organizations 
or any place that requires security.
  - Efficient and time-saving compared to the traditional method that calls names one by one.
  - The system identifies faces in live video input from a camera.
  - The algorithm will construct a boundary for each face candidate.
  - The system will compare faces with the provided database.
  - If the face doesn’t match with anyone from the database the system will label it as unknown.
  - Since the live input of one’s face must match with the saved data, calling another person’s name for roll call (faking attendance) is impossible.

## Technological Stack 
* Project Description 
* OpenCV, which is a popular computer vision library in Python.
* Firebase Real Time Database, which is a NoSQL cloud database.

## User Stories 
1. As a User I want to be able to choose the camera which connects to the software so that I could use the preferable device. 
2. As a User I want to be able to add data about people in my database so that the information about them would be stored in one place.
3. As a User I want to be able to add new people to my database so that they would also be included.
4. As a User I want to be able to add pictures of people in my database so that they would be recognized by the software.
5. As a User I want to be able to access to the real-time database that is linked with the face recognition attendance system so that I can see people in my database.
6. As a User I want to be able to change data about people in my database so that the information could be up-to-date in case of any changes.
7. As a User I want to be able to change pictures of people in my database so that it would be up-to-date in case of any changes in appearance.
8. As a User I want to be able to remove a person from my database in case someone is not part of the organization, school, or etc any more so that the system wouldn't recognize them anymore.
9. As a User I want to be able to use a face recognition system to monitor entry from the place so that it can quickly and accurately record the attendance.
10. As a User I want to have the attendance system that recognizes people's face saved in the database so that I don't have to check their face one by one and compare with ID or anything that can verify the identity.
11. As a User I want to be able to see profile picture, name and ID of a person on the screen when someone takes the attendance so that I get know his/her details without checking their ID card.
12. As a User I want to be able to view total attendance of a person till the current time on the screen when someone takes the attendance for convenience so that I don't have to access my database to check everytime.
13. As a User I want to be able to set the time limit after which one person can be marked again so that it can fit my purpose for using this software.
14. As a User I want a notification to appear if someone has already took attendance within the time limit so that there is no duplicate attendance saved in the database.
15.	As a User I want to have the attendance system that automatically update my attendance database when someone checks the attendance so that I don't need to manually fill in attendance sheets which will save time and reduce the risk of errors.
16. As a User I want to be able to view data about specific person in my database so that I can find the information I'm currently looking for.
17. As a User I want to be able to see when was the last time someone was present so that I don't have to check it manually.
18. As a User I want to be able to see how many people are in my database so that I don't have to count them manually.


