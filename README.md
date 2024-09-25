

# Image to Sketch Converter

This Python project converts an image to a outline sketch using OpenCV. The image is manually provided by specifying its path, and the resulting sketch is saved in the same directory.

## Features
- Convert images into sketches using OpenCV.
- Save the output sketch in the same folder as the input image.

## Installation

   1.**Install cv2 library by enetering this into windows command prompt:** <br>
    ```
    pip install opencv-python-headless
    ```
    
    
2. **Clone the repository:**
   ```
   git clone https://github.com/your-repo/image-to-sketch-converter.git
   cd image-to-sketch-converter
   ```

3. **Install dependencies:**
   Make sure you have Python installed, then install the required libraries using pip:
   ```
   pip install opencv-python
   ```

## How to Use

1. Place your input image in the desired directory.
2. In the code, manually specify the path of the image you want to convert.
   ```python
   img_path = 'path/to/your/image.jpg'
   ```
3. Run the Python script:
   ```
   python sketch_converter.py
   ```
4. The generated sketch will be saved in the same directory with a different filename (e.g., `sketch_image.jpg`).

## Example

If you have an image at `images/photo.jpg`, simply edit the script like so:
```python
img_path = 'images/photo.jpg'
```

After running the script, a sketch version of the image will be saved as `sketch_photo.jpg` in the same folder.

---

## Future Scaling :
- Build a front-end interface to make image uploading easier.
- Deploy the project to make it accessible online.

---
