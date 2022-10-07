# Car plate recognition (YOLOv5, EasyOCR)

# To measure the accuracy of the object detector, the method of Intersection over Union (IOU)

__Task:__
The company needs to recognize the license plates of cars to understand whether to open the barrier or not. The car drive up to the barrier, the camera is directed at the car and provides information. The car plate is recognized, if the number is not recognized, then the barrier remains lowered, otherwise the barrier rises and passes the car into the territory. Currently, image recognition is taking place, there is no example of the video stream working.


Batch - 6, epochs - 30, optimizer - SGD<br />
Accuracy: 0.7244897959183674


Batch - 6, epochs - 30, optimizer - Adam<br />
Accuracy: 0.6931818181818182


Batch - 6, epochs - 10, optimizer - SGD<br />
Accuracy: 0.8556701030927835 

Instruction manual:<br />
1. Open the CarPlateRecognition.ipynb file in Google Colab<br />
2. Download file best.pt(link to the google drive below) and place it in the Google Colab files of your notebook<br />
3. Add an image to the Google Colab files of your notebook<br />
4. Replace the word PATH in notebook with your file path<br />
5. Let's try to recognize the car plate number<br />


You can find the files on the disk(train images, test images, train.csv, file with best weights for detection) - https://drive.google.com/drive/folders/11P7l5HYZpt4Y2nMm2wG9IUhruDTtJ8yx?usp=sharing
