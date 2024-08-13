# Image Stitching 

## Description

This project stitches multiple images together to create a panoramic image(orthomosaic). The script loads all images from a specified folder, stitches them together using OpenCV's `Stitcher` class, and saves the resulting panoramic image.

## Features

- Load images from a specified folder.
- Stitch images to create a panoramic view.
- Save and display the resulting stitched image.

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.6+
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/image-stitching.git
    cd image-stitching
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Stitch Images

1. Place your images in a folder, e.g., `home`.
2. Modify the notebook  to point to your image folder:
    ```python
    image_folder = r'C:/Users/rajuv/Desktop/home'
    ```
3. Run the notebook.

4. The resulting stitched image will be saved as `stitched_image.jpg` in the current working directory and displayed using `matplotlib`.


Here’s a README.md file for your image stitching script:

markdown
Copy code
# Image Stitching Script

## Description

This project stitches multiple images together to create a panoramic image. The script loads all images from a specified folder, stitches them together using OpenCV's `Stitcher` class, and saves the resulting panoramic image.

## Features

- Load images from a specified folder.
- Stitch images to create a panoramic view.
- Save and display the resulting stitched image.

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.6+
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/image-stitching.git
    cd image-stitching
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Stitch Images

1. Place your images in a folder, e.g., `home`.
2. Modify the script to point to your image folder:
    ```python
    image_folder = r'C:/Users/rajuv/Desktop/home'
    ```
3. Run the script:

    ```sh
    python image_stitching.py
    ```

4. The resulting stitched image will be saved as `stitched_image.jpg` in the current working directory and displayed using `matplotlib`.

## Dependencies
Ensure you have the following libraries installed:
opencv-python
matplotlib
numpy

You can install these dependencies using the following command:

```sh
pip install opencv-python matplotlib numpy


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions, suggestions, or feedback, please contact us at raju.venkateshkumar@gmail.com 

## FAQ
What image formats are supported?
Currently, the script supports JPG format for stitching.

How do I change the output file name?
You can change the name of the output file by modifying this line in the script:
```
cv2.imwrite('stitched_image.jpg', stitched_image)
```
What happens if the stitching process fails?
If the stitching process fails, the script will print an error message: "Error during stitching process".
