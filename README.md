# Smart-Attendence-System-using-opencv
•	In this project we used cv2 library to convert the images from BGR to RGB in dataset. numpy  used for mathematical calculations and csv is used to store aSttendance of student. We used face_recognition library  to recognize face of student and smtplib is used for mail.
•	We stored directory of dataset in one variable using os library after that we read each image from that list and append that image into new list.
•	We made one function in which we take encoding of each image from that list using cv2 and face_recognition libraries after that store thsese encoded images into new list and return that list.
•	We gave three choice to user i.e. take attendance ,registration and send attendance.
•	In take attendance, we access webcam using opencv after that we compare the image of the user with encoded images in the list. If the face matches with encoded image then store the attendance into the excel file using csv library
•	In registration, we take name as input from user after that access the camera to take a picture and store that picture into the dataset.
•	In send attendance, we send the csv file to the respective teacher using smtp library.

