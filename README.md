# Detection-and-Recognition-of-illegally-parked-vehicles

Using object detection and vehicle number plate recognition algorithms to detect illegally parked vehicles in no parking areas

# Current State

At the moment the program is in a sort-of-working state. Any problems that arise are being fixed.  

# Set Up

1. Clone [GitHub Repository](https://github.com/sai-jeelakarra/Detection-and-Recognition-of-illegally-parked-vehicles.git)

2. Install Dependencies:
  `pip install -r requirements.txt`

3. Add yolov3.weights from [here](https://pjreddie.com/media/files/yolov3.weights) to the yolo-coco directory.

4. Add frozen_east_text_detection.pb from [here](https://github.com/oyyd/frozen_east_text_detection.pb/blob/master/frozen_east_text_detection.pb) to the main directory.

5. Install the pytesseract binary from [here](https://github.com/UB-Mannheim/tesseract/wiki). Add/Update the appropriate path to the tesseract.exe file to text_recognition.py file.

6. Run the program with command:
  `python main.py -i <path/to/sample.image> -y yolo-coco`
  
**Original Repository:** <https://github.com/sai-jeelakarra/Detection-and-Recognition-of-illegally-parked-vehicles>
