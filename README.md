# Car Number Plate Detection

This project detects and extracts car number plates from a live video stream using OpenCV and a Haar Cascade classifier.

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- OpenCV (cv2)
- NumPy

## Installation

1. Clone this repository:

   
   git clone https://github.com/sachit16/Car-Number-Plates-Detection.git


2. Install the required Python packages:


   pip install opencv-python numpy


## Usage

1. Run the `car_number_plate_detection.py` script:

   
   python car_number_plate_detection.py
   

2. The script will open a window displaying the live video stream from your webcam.
   
3. When the script detects a number plate, it will draw a rectangle around it and display the extracted plate in a separate window.

4. Press the 's' key to save the extracted plate. The saved images will be stored in the `plates` folder.

## File Structure

---bash
Car-Number-Plates-Detection/
│
├── model/
│   ├── haarcascade_russian_plate_number.xml
│
├── plates/
│   ├── scaned_img_0.jpg
│   ├── scaned_img_1.jpg
│   └── ...
│
├── car_number_plate_detection.py
│
└── README.md
---

## Credits

This project is inspired by [Car-Number-Plates-Detection](https://github.com/sachit16/Car_Number_Plate_Detection) by [Sachit Bhor](https://github.com/sachit16).


