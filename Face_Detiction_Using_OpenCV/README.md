# Face_Detiction_Using_OpenCV



```markdown

This simple Python script utilizes the OpenCV library to perform face detection in an image and draw rectangles around the detected faces. The script uses a pre-trained Haar Cascade classifier for frontal face detection.

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
2. Ensure you have an image for testing (e.g., 'Media/test 2.jpg').
3. Make sure the Haar Cascade XML file ('Trained_Classifier/haarcascade_frontalface_default.xml') is available in your project directory.
4. Run the script:

    ```bash
    python Face_Image_detection.py
    python Face_Vedie_detection.py
    ```

5. The script will display the input image with rectangles drawn around the detected faces.

## Customization

Feel free to experiment with the parameters in the `detectMultiScale` function for better face detection performance in different scenarios. Additionally, you can use your own images for testing.

## Contributing

Contributions are welcome! If you find any issues or have improvements, please open an issue or create a pull request.

## Author

- [Hassan Anwar]


![Sample Image](https://github.com/hassancodeanwar/Instant_Training_Projects/blob/main/Face_Detiction_Using_OpenCV/media/WhatsApp%20Image%202024-02-11%20at%2017.35.28_a57076cb.jpg)
