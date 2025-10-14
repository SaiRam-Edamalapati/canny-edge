# WORK SHOP:0 3CANNY EDGE DETECTION

<H3>Name: DHANUSH C</H3>
<H3>Register no: 212224040066</H3>
<H3>Date: 14.10.2025 </H3>

# AIM:
To perform Canny Edge Detection model through your laptop.

# PROGRAM:
```
import cv2
import matplotlib.pyplot as plt
```
```
img = cv2.imread('Dhanush.jpg',cv2.IMREAD_GRAYSCALE)
```
```
blurred =cv2.GaussianBlur(img, (5,5),0)
```
```
edges = cv2.Canny(blurred, 50, 150)
```
```
plt.figure(figsize=(10,5))
plt.subplot(121),plt.imshow(img, cmap='gray')
plt.title('Original Image'), plt.axis('off')
plt.subplot(122),plt.imshow(edges, cmap='gray')
plt.title('Detected Edges'), plt.axis('off')
plt.show()
```

# OUTPUT:

<img width="969" height="546" alt="Screenshot 2025-10-14 150936" src="https://github.com/user-attachments/assets/4f0d3404-ff4f-4608-8239-62f20acd4b0c" />


 
