# WORK SHOP: 03CANNY EDGE DETECTION

<H3>Name: Sai Ram E</H3>
<H3>Register no: 212224240141</H3>

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

<img width="794" height="236" alt="image" src="https://github.com/user-attachments/assets/c875723e-7b4f-439c-a5d2-e65f93858cae" /> 
