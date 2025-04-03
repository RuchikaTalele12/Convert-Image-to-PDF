Introduction :
The code given is a simple Graphical User Interface (GUI) application created using the Tkinter library in Python. The application for helping any user convert multiple images into a single Portable Document Format (PDF) file. The user does the selection of images they want to convert and provides the name and location of the resulting PDF file to the interpreter. The application uses the Python Imaging Library (PIL) to handle the conversion process.

Functions Used in Above Program:
1. ‘images_to_pdf‘: This function takes a list of images and the name of a PDF file as inputs. creates a new PDF file with the info given, and appends the images to it. If the conversion process is successful, it shows successful feedback/message to the user, otherwise, it shows an error.

2. ‘select_images‘: This function opens a file selection dialog allowing users to select one or more than one image file.

3. ‘select_pdf’: The function will help open a dialog box allowing users to specify the name and path of the PDF file for its creation.

Finally, the mainloop() function is a common Python function invoked and used in Python’s GUI-based programs where the function creates a GUI event loop and keeps the window open until the user chooses to close it

