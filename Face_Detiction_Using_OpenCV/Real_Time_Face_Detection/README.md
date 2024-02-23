# Real-Time Face Detection using OpenCV

This Python script utilizes the OpenCV library to perform real-time face detection from a webcam feed. The script captures video frames, converts them to grayscale, and uses a pre-trained Haar Cascade classifier for frontal face detection. Rectangles are drawn around the detected faces in real-time.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python (3.x recommended)
- OpenCV library (`pip install -r requirements.txt`)

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository or download the script.
2. Ensure you have a webcam connected to your system.
3. Make sure the Haar Cascade XML file ('pretrained_classifier/haarcascade_frontalface_default.xml') is available in your project directory.
4. Run the script:

    ```bash
    python real_time_face_detection.py
    ```

5. The script will open a window displaying the webcam feed with rectangles drawn around the detected faces. Press the 'Esc' key to exit the program.

## Customization

Feel free to experiment with the parameters in the `detectMultiScale` function for better face detection performance in different scenarios.

## Contributing

Contributions are welcome! If you find any issues or have improvements, please open an issue or create a pull request.

## Author

- Hassan Anwar

![Real-Time Face Detection](https://github.com/hassancodeanwar/Instant_Training_Projects/blob/main/Face_Detiction_Using_OpenCV/media/Real-Time_face_detiction.gif)
