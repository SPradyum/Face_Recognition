# Face_Recognition
This project focuses on implementing a face recognition system using the powerful K-Nearest Neighbors algorithm. Face recognition is a captivating field with numerous applications, ranging from security systems to personalized user experiences.

Algorithm: K-Nearest-Neighbour

Setup:
Things you require to run this code are:
1. Python Supporter IDE (recommended - Visual Studio Code)
2. Python installed on your computer
3. Python Libraries:
   -  cv2 : 'pip install opencv-python'
   -  numpy : 'pip install numpy'
   -  pickle : 'pip install pickle'
   -  sklearn : 'pip install scikit-learn'
   -  os : 'pip install os_command_py'

Insights:
1. This project is excecuted using 2 python files, which contains the code and 1 folder where the trained data is stored.
2. This module is trained and tested at real-time data.
3. This porject uses the camera of the device to recognize the face.
4. The Face is recognized using the help of pixels.
5. When a new data is inserted, it is mandatory to label the new data to reduce complexity and confusions.
6. When we insert new data label than, the module will access the camera of the device and analyse the data in front of it and stop the running process.

Working:
1. To run this project, we first need to train the module with new data;
   - run the 'add new face.py' file.
   - Enter the label of the data.
   - The module will analyse the data and end the running process.
2. Your module is now trained with your data and has it in the "data" folder.
3. To test the data:
   - run the 'face recognition.py' file.
   - a pop-up window of device camera will appear.
   - the module will start displaying the trained data on the screen with its label.

NOTE: The module can get confuse sometimes as the lighting and environment may effect the module to recognize.
