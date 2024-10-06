In order to run the code please make sure to upload the desired Neon Color image into your Google Drive, please insert the path to the folder that contains the image in line 6.

from google.colab import drive
drive.mount('/content/drive/')

%cd 'YOUR_GOOGLE_DRIVE_FOLDER_PATH'
%ls
import os
path = os.getcwd()
print('path: ' + path)

then
