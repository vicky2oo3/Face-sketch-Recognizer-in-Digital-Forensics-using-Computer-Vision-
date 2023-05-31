# Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-
JAVA PROJECT FOR USING AWS (MACHINE LEARNING)


![Transparent Logo](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/7f52c8a2-44e1-4edd-97f7-1578ac13a92b)



step1:

Souce code press the Link:https://drive.google.com/file/d/1InnMp9caT3QNzbSbpJCeaUadGt14qDor/view?usp=share_link
step2:
1. Download the Source Code from the Repo (https://github.com/imakashsahu/Third-Eye-Final-Year-Project)
2. Download and Install the Java JDK 8 (https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html)
3. Download the latest NetBeans Installer (https://netbeans.apache.org/download/index.html)
3. Install and Open NetBeans
4. GoTo Tools > Plugin > Available Plugin 
5. Search for "Java FX" and check "Gluon Plugin" & "JavaFx implementation for Windows" then click on Install
6. Now search for "Maven" and check "Gradle" then click on Install
7. Restart NetBeans


 step3:


9. This part 1 of the project is been build using JAVA FX
10. Download Scene Builder (https://gluonhq.com/products/scene-builder/)
11. GoTo tools > options > Java > JavaFx
12. Browse for the Scene Builder Directory and select the directory from C:\ProgramFiles
13. Now GoTo File > Open Project > ThirdEye v2
14. Now under projects click on "ThirdEye v2 > Libraries" Right Click and select "Add Jar"
15. Browse to "ThirdEye v2 > lib" and select all and open
16. Download and Install SQLite Browser (https://sqlitebrowser.org/dl/)
17. Open the "login.sqlite" file from the "ThirdEye v2" Folder
18. Add your Own Creds this is Important to get the OTP to login
19. Turn On Less secure for you Gmail (https://myaccount.google.com/lesssecureapps)
20. Now go to NetBeans, under projects click on "ThirdEye v2 > Source Package > thirdeye.v2" Double click on Login_screenController.java
21. On Line 144, Enter your GMail Creds to send OTP
22. Run the Project (F6)
23. Enter the Credential from DB Lite
24. Enter the OTP received to the email 
25. Select Create Sketch and your are good to go 
26. Change the File Directory on line 508 of file "dashboard_controller.java"!!!!!


step4:


1. This part 2 of the project is been build using JAVA Maven and AWS for Deep learning
2. This part requires you to have AWS account with Credit Card been added to be activated
3. Create a AWS Free Tier account by adding in your Credit Card
4. Create a IAM user profile for the JAVA (https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html)
5. Add S3 and Rekognition Full Access
4. Install AWS CLI on Windows (https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html)
5. Run "aws configure" in CMD
5. Create a s3 Bucket 
6. Now GoTo File > Open Project > ThirdEye_FaceMatch
7. Create a S3 Bucket on the AWS console
8. Create a collection in s3 using the "collection_create.java" file
9. Add images to the collection using the "collection_add_image.java" file
10. Enter the S3 Bucket name and collection details in the "collection_search_face.java" file
11. Run the Project (F6)


OUTPUTS
![Screenshot (39)](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/93a75670-ac09-497f-839b-e14e026eb1a4)

![Screenshot (40)](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/991bbf70-7602-4ac4-a634-e591ad668931)

![Screenshot (41)](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/4e95c108-748f-47e2-bef4-0e9a3d4af512)

![Screenshot (42)](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/12b18c18-2eae-4b79-90a6-883b8730a92a)

![photo_6201739639790877244_y](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/986330c0-8deb-4ff7-aeee-3a2b72fe557b)

![photo_6201739639790877246_y](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/e2fcb924-e25d-4835-8da6-2a52c7e51176)

![photo_6201739639790877247_y](https://github.com/vicky2oo3/Face-sketch-Recognizer-in-Digital-Forensics-using-Computer-Vision-/assets/109359190/eb7bd070-d708-4988-8184-9e2a10dbf901)
