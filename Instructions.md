In order to run the code please make sure to upload the desired Neon Color image into your Google Drive, please insert the path to the folder that contains the image in line 6.

from google.colab import drive
drive.mount('/content/drive/')

%cd 'YOUR_GOOGLE_DRIVE_FOLDER_PATH'
%ls
import os
path = os.getcwd()
print('path: ' + path)

Then in the following block of code insert (in line 16) the name on the desired input image that stored in the above folder location you inserted:

bgr_image = cv2.imread('YOUR_IMAGE_NAME.png')
rgb_image = cv2.cvtColor(bgr_image, cv2.COLOR_BGR2RGB)
plt.imshow(rgb_image, cmap='gray')
plt.axis('off')
plt.title('Original image')
plt.show()

height, width = rgb_image.shape[:2]
for i in range(height):
  for j in range(width):
    if not np.array_equal(rgb_image[i, j], [255, 255, 255]) and not np.array_equal(rgb_image[i, j], [0, 0, 0]):
      y = i
      x = j
      break

y_chrom = y
x_chrom = x

y_background = 0
x_background = 0

Now you are ready to run the code :)
