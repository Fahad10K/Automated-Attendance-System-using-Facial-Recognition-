# Automated-Attendance-System-using-Facial-Recognition-
Using OpenCV and Machine Learning Algorithms, we have created an automated attendance system. 


In order to determine classroom attendance, face detection and face recognition are performed. Face detection is used to determine the location of the faces in the classroom image and extract sub images for each face. Then, in face recognition, the face images detected will be compared with the data base consisting of images of students in the class, and attendance will be recorded accordingly

![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/a182887a-96b4-4977-ad1d-95486657b419)


Our code using HOG to find faces and isolate them from the background 
 Then we use face landmark estimation. The basic idea is we will come up with 68 specific points (called landmarks) that exist on every face — the top of the chin, the outside edge of each eye, the inner edge of each eyebrow, etc. Then we will train a machine learning algorithm to be able to find these 68 points.
Next to recognize unknown faces from known faces we measure the distances of facial features using Deep CNN to generate 128 measurements of each known faces and then compare it with the known faces.
Next we use a simple SVM classifier algorithm to classify an unknown face to a known face to finally tell who the new image is of and mark the attendance in a .csv file.

![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/5b035844-ca8d-49c9-8970-58585001c6da)


By using a PYTHON code, We’re going to use a method invented in 2005 called Histogram of Oriented Gradients — or just HOG for short to find faces in an image.
The python code then uses facial landmark estimation along with deep CNN to generate 128 measurements 
And then finally we use simple SVM classifier to recognize the person in the video

![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/30401c2f-ad37-446b-98a9-ca23c0088f37)

![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/ea4e48fd-d00c-440f-a22b-8d9f7b8589eb)



![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/dabb1be3-8ec3-41e6-b145-9c4461a12052)

![image](https://github.com/Fahad10K/Automated-Attendance-System-using-Facial-Recognition-/assets/92253772/e585f12b-9edc-4c38-9f11-c985ccea9e43)


