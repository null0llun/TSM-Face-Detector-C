# TSM-Face-Detector

Export the containing files and folder in a directory of your choise.
Run the command shell inside the directory and execute the command (there is a makefile in the directory).
- make all

The output file that is created is named myFaceDetector.
The models and settings files are saved in "models/" folder.
There are some sample images in the "images/" folder.

Change the settings xml file contents according to your needs.
Change the <outputType> xml object value to
-xx1 (binary) for export the results in XML file
-x1x (binary) for export the results in image file
-1xx (binary) for export the results in visualy in the screen

Run the command
- ./myFaceDetector [image_path] [model_path] [settings_path]

