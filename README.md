# 1) Develop a program to display grayscale image using read and write operations

import cv2
img= cv2.imread(&quot;app.jpg&quot;)
gray_image=cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
cv2.imwrite(&quot;opencv-greyscale.png&quot;,gray_image)
cv2.imshow(&quot;Gray_Scale&quot;,gray_image)
cv2.waitKey(0)
cv2.destroyAllWindows()

# output:
![image](https://user-images.githubusercontent.com/72402606/104429706-f00bb600-55ab-11eb-9f9c-47be74cb7566.png)


# 2) Develop a program to perform a linear transformation for an image
(scaling &amp; rotation)
a. Scaling:
import cv2 as c
import numpy as np
img= cv2.imread(&quot;app.jpg&quot;)
h,w=img.shape[0:2]
width=int(w*1)
hight=int(h*1)
dim =(width,hight)
res=c.resize(img,dim)
c.imshow(&quot;Scaling&quot;,res)
c.waitKey(0)
c.destroyAllWindows()

# Output:
![image](https://user-images.githubusercontent.com/72402606/104431462-eb480180-55ad-11eb-9a2a-19989d09936a.png)
