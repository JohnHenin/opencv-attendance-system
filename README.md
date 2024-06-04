This project is used for accessing the webcam using Opencv and to get the attendance of the person in front of the camera ehich is then stored in a .csv dataset.

First the add_faces.py is to be executed which takes a 100 frame of the user and asks for the name of theb user, then it registers the content as a pickle file
as names.pkl and face_data.pkl

The 100 frames are stored as .png files in the output_images folder which can be used for image dataset.

Test.py is to be executed next which accesses the background img and identifies the user's name by the bounding boxes in the Webcam.

Press 'o' in the keyboard to take attendance to store name and time in a .csv file

app.py is used to stream the dataset values in a streamlit platform
