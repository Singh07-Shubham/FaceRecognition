# FaceRecognition

#### install the dependencies in a virtual environment by following this link
https://github.com/ageitgey/face_recognition

create folder structure like below inside a folder named PROJECT:

1. face_rec_example.py

2. known_faces(folder)

     -folder1(subfolder)
     -folder2(subfolder)
     --etc ..
     
3. unknown_faces(folder)
     -img.jpg
     -img2.jpg
     .....etc.. 
     
4. test_face_result(folder)
    --after running the python file recognised faces from unknown_faces directory will be saved here
    
To run -

activate your created viurtual environment for this project (conda or venv)
go to the project directory
then run :- python face_rec_example.py
output will be displayed on screen and also saved in test_face_result folder
