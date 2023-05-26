# Optical-Character-Recognition

## About the Project
This project is a Python-based Optical Character Recognition (OCR) application using the EasyOCR library. It provides a convenient way to detect and recognize text in images, making it useful for a wide range of applications such as document processing, image captioning, and text extraction.

The code in this project showcases how to use EasyOCR to extract text from images. It follows these steps:

 - Import the necessary libraries: cv2, easyocr, numpy, and matplotlib.pyplot.

 - Specify the path to the input image.

 - Initialize an EasyOCR reader with the desired language(s) for text recognition.

 - Read text from the image using reader.readtext().

 - Extract the recognized text and the corresponding coordinates of the text regions.

 - Visualize the image with annotated bounding boxes around the detected text regions and the recognized text displayed.

 - Save the extracted text to a .txt file.

## Required Libraries

 - Python
 - OpenCV
 - EasyOCR
 - NumPy
 - Matplotlib

## Installation

This is make you understand how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.

 - Clone the repo
```
git clone https://github.com/KalyanMurapaka45/Optical-Character-Recognition.git
```

 - Install the required libraries
```
pip install -r requirements.txt
```
 - Open  ```Optical Character Recognition.ipynb``` file and Execute it.
 

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!. ```Don't forget to star the project if you find it useful!```

1. Fork the Project

2. Create your Feature Branch

3. Commit your Changes

4. Push to the Branch

5. Open a Pull Request

## Licnese

Distributed under the GNU General Public License v3.0. See ```LICENSE.txt``` for more information.

## Acknowledgements

We would like to express our gratitude to the open-source community for their invaluable inspiration and contributions. We also acknowledge the Python libraries used in this project and their respective contributors.
