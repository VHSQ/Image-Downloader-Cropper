# Image-Downloader-Cropper
A Python GUI that allows users to download images from the internet by inputting image address and or dragging file from computer. Users can crop images and save them. 

### Description
This Python application allows users to download images from the internet using URLs, preview them, and optionally crop them to save locally. Built with Tkinter for the GUI, it supports drag-and-drop functionality for files installed on computer. This provides ease of use and it provides a visual progress bar for downloads. 

### Features
Download images using URLs.
Preview downloaded or dropped images within the application.
Crop images interactively and save the cropped version.
Progress bar for visual feedback during image downloads.
Drag and drop image files directly onto the application for quick loading (Only for files on pc).
Simple and intuitive graphical user interface.

### Installation
Before running the application, ensure you have Python installed on your system. This application requires Python 3.x.

### Dependencies
Tkinter (usually comes with Python)

PIL (Python Imaging Library), install via pip:

pip install Pillow
tkinterdnd2, install via pip:

pip install tkinterdnd2
Requests, install via pip:

pip install requests

### Running the Application
Clone the repository or download the source code. Navigate to the directory containing the application and run:

python image_downloader_app.py
Replace image_downloader_app.py with the actual name of your Python script if it's different.

### Usage
Download Image: Enter the image URL in the URL field and specify the directory where the image should be saved. Click "Download Image" to start the download.
Preview and Crop: The downloaded image will automatically be displayed in the preview area. Click "Crop" to select a portion of the image, then "Save Crop" to save the cropped image in the specified directory.
View Full Size: Click on the preview image to open it in full size in a new window.
Drag and Drop: You can also drag and drop an image file onto the application to load it directly into the preview area.

### Contributing
Contributions to the project are welcome! Please fork the repository and submit a pull request with your proposed changes or improvements.

### License
Specify the license under which your project is made available. Common choices include MIT, GPL, and Apache 2.0.
