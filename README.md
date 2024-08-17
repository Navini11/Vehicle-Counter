# Vehicle Counter Project

This repository contains the implementation of a vehicle counter system that detects and counts vehicles in different lanes. The project utilizes computer vision techniques powered by OpenCV and deep learning models with TensorFlow.

![image](https://github.com/user-attachments/assets/d22c5690-6a9e-4cd4-8d1f-a42f77e3a4ba)

## 📄 Contents

- `License Plate Detection.py`: A script for detecting and recognizing license plates on vehicles.
- `Vehicle Counting in Lanes.py`: A script for detecting and counting vehicles in specified lanes.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- OpenCV
- TensorFlow
- Other dependencies as specified in `requirements.txt`

You can install the required packages using pip:
```bash
pip install -r requirements.txt
```

### Running the Scripts

1. **Clone this repository to your local machine:**
    ```bash
    git clone https://github.com/Navini11/vehicle-counter.git
    cd vehicle-counter
    ```

2. **Run the Vehicle Counting Script:**
    ```bash
    python Vehicle Counting in Lanes.py
    ```

3. **Run the License Plate Detection Script:**
    ```bash
    python License Plate Detection.py
    ```

## 🛠️ Project Overview

### Vehicle Counting

The `Vehicle Counting in Lanes.py` script performs the following steps:
1. **Load Video Feed:** Loads a video stream for vehicle detection.
2. **Preprocessing:** Applies preprocessing techniques such as resizing and grayscale conversion.
3. **Vehicle Detection:** Uses a pre-trained deep learning model to detect vehicles in each frame.
4. **Lane Assignment:** Assigns detected vehicles to specific lanes based on their positions.
5. **Counting:** Counts the number of vehicles in each lane and updates the count in real-time.

### License Plate Detection

The `License Plate Detection.py` script includes:
1. **Load Image/Video Feed:** Loads an image or video stream containing vehicles.
2. **Preprocessing:** Applies preprocessing techniques such as resizing and grayscale conversion.
3. **License Plate Detection:** Uses OpenCV to detect license plates on vehicles.
4. **Recognition:** Recognizes the characters on the detected license plates using OCR.

## 📚 Technologies Used

- **Software:**
  - TensorFlow
  - OpenCV
  - Google Colab (for model training)
  - Visual Studio Code

- **Hardware:**
  - Any standard computer with Python environment

## 🏆 Achievements

- Successfully detected and counted vehicles in multiple lanes with high accuracy.
- Efficiently recognized and extracted license plate information from vehicles.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

