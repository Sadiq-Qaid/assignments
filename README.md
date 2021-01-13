1) Develop a program to display grayscale image using read and write operations

import cv2
img= cv2.imread(&quot;app.jpg&quot;)
gray_image=cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
cv2.imwrite(&quot;opencv-greyscale.png&quot;,gray_image)
cv2.imshow(&quot;Gray_Scale&quot;,gray_image)
cv2.waitKey(0)
cv2.destroyAllWindows()

output:
![image](https://user-images.githubusercontent.com/72402606/104429706-f00bb600-55ab-11eb-9f9c-47be74cb7566.png)
