# Car-Traffic-Recognition-in-Images

This project focuses on detecting cars in traffic images using Python, OpenCV, NumPy, and other libraries. The implementation is done in Google Colab, making it accessible and easy to run for anyone interested in understanding or utilizing the code.

## Features
- Utilizes OpenCV for image processing
- Implements Canny edge detection for identifying edges in the images
- Utilizes bilateral filter for noise reduction and edge preservation
- Processes image contours and masks for car detection

## Installation
To run the project, make sure to have the following dependencies installed:
- Python
- OpenCV
- NumPy
- Google Colab or Jupyter Notebook

You can install OpenCV and NumPy using pip:
```bash
pip install opencv-python
pip install numpy
```

## Usage
1. Clone the project repository or download the project files.
2. Open the main Python script in Google Colab or Jupyter Notebook.
3. Run the script, and it will process the traffic images provided in the project.

## How It Works
The main script reads the traffic images and applies Canny edge detection to identify edges. It then utilizes a bilateral filter for noise reduction and preservation of edges. The processed images are used to find and draw contours and masks for car detection.

## Contributing
If you want to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Your contributions are highly appreciated.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- This project was inspired by the need for efficient car detection in traffic images.
- Thanks to the contributors of OpenCV and NumPy for providing powerful tools for image processing in Python.

Feel free to reach out if you have any questions, suggestions, or feedback!  
