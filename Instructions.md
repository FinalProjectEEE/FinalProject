In order to run the code please make sure to upload the desired Neon Color image (there are 4 such images in Source Images folder) into your Google Drive, then please find the following lines of code in ProjectCode.ipynd and insert the path to the folder that contains the image:

>from google.colab import drive
>drive.mount('/content/drive/')

>%cd 'YOUR_GOOGLE_DRIVE_FOLDER_PATH'

Then please find the following line of code and insert the name on the desired input image that you stored in the above folder location you inserted:

>bgr_image = cv2.imread('YOUR_IMAGE_NAME.png')

Now you are ready to run the code :)
