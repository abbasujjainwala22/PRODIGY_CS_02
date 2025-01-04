# IMAGE ENCRYPTION DECRYPTION APPLICATION

# Description:

This is a Python application built using Tkinter for GUI and OpenCV for image processing. It allows users to encrypt and decrypt images using a simple interface. The encryption algorithm used here is a basic one where each pixel value of the image is divided by a randomly generated key matrix and saved as an encrypted image. The decryption process involves multiplying the encrypted image with the same key matrix to obtain the original image.

# How to Use:

1. Run the script 'image_encryption_decryption.py'.
2. Click on the "Choose" button to select an image from your local system.
3. Once the image is selected, it will be displayed in the "Original Image" section.
4. Click on the "Encrypt" button to encrypt the selected image.
5. The encrypted image will be displayed in the "Encrypted/Decrypted Image" section.
6. Click on the "Decrypt" button to decrypt the encrypted image.
7. The decrypted image will be displayed in the "Encrypted/Decrypted Image" section.
8. You can save both the encrypted and decrypted images using the "Save" button.
9. Additionally, you can download the encrypted and decrypted images using the respective "Download" buttons.
10. To reset the image to its original format, click on the "Reset" button.
11. Click on the "EXIT" button to close the application.

# Code Structure:

- The code begins with importing necessary libraries including Tkinter, PIL (Python Imaging Library), OpenCV, and others.
- It defines global variables and functions required for image processing and GUI operations.
- Functions like 'openfilename()' and 'getpath()' help in selecting and processing image files.
- The main GUI layout is created using Tkinter widgets like Labels, Buttons, and FileDialogs.
- Functions for image encryption ('en_fun()'), decryption ('de_fun()'), resetting ('reset()'), and saving images ('save_img()') are defined.
- Additional functions for downloading encrypted and decrypted images are also included.
- The application window is configured with a protocol to handle window closing.
- Finally, the main event loop 'window.mainloop()' is called to run the application.

# Usage:

- This application can be used by anyone who wants to encrypt and decrypt images quickly and easily.
- It can be used for educational purposes to understand basic image encryption techniques.
- Users can integrate this code into larger projects requiring image encryption functionalities.

# Example:

Suppose you have an image file named "sample_image.jpg" that you want to encrypt and decrypt using this application:

1. Run the script 'image_encryption_decryption.py'.
2. Click on the "Choose" button and select the "sample_image.jpg" from your local system.
3. Click on the "Encrypt" button to encrypt the image.
4. The encrypted image will be displayed.
5. Click on the "Decrypt" button to decrypt the encrypted image.
6. The decrypted image will be displayed.
7. You can save both the encrypted and decrypted images using the "Save" button.
8. Additionally, you can download the encrypted and decrypted images using the respective "Download" buttons.
9. To reset the image to its original format, click on the "Reset" button.
10. Finally, click on the "EXIT" button to close the application.
