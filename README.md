```
import cv2
image=cv2.imread('wallpaper.jpg',1)
image = cv2.resize(image,(500,500))
cv2.imshow('Image Window', image)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(500,500))
res = cv2.line(img, (0, 0), (500,500), (200, 100, 205), 10)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(500,500))
res = cv2.circle(img,(250,250), 150, (255, 0, 0), 10)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(500,500))
res_img = cv2.rectangle(img, (500-10,500-10), (0+10,0+10),(100, 255, 100), 10)
cv2.imshow('Image Window', res_img)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(500,500))
font = cv2.FONT_HERSHEY_SIMPLEX
res = cv2.putText(img,"Opencv_drawinG", (10,50), font,1, (255, 255, 255),2)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg',1)
img = cv2.resize(img,(500,500))
cv2.imshow('Original Image',img)
hsv2 = cv2.cvtColor(img,cv2.COLOR_RGB2HSV)
cv2.imshow('RGB2HSV',hsv2)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg',1)
img = cv2.resize(img,(400,400))
cv2.imshow('Original Image',img)
gray2 = cv2.cvtColor(img,cv2.COLOR_RGB2GRAY)
cv2.imshow('RGB2GRAY',gray2)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg',1)
img = cv2.resize(img,(400,400))
cv2.imshow('Original Image',img)
YCrCb1 = cv2.cvtColor(img, cv2.COLOR_BGR2YCrCb)
cv2.imshow('RGB-2-YCrCb',YCrCb1)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg',1)
img = cv2.resize(img,(400,400))
cv2.imshow('Original Image',img)
BGR = cv2.cvtColor(img,cv2.COLOR_HSV2BGR)
cv2.imshow('HSV2RGB',BGR)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg', 1)
img = cv2.resize(img, (400, 400))
cv2.imshow('Original Image', img)
pixel_value = img[100, 100]
print(f"Pixel value at (100, 100): {pixel_value}")
img[199, 199] = [255, 255, 255]
cv2.imshow('Modified Image', img)

cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread('wallpaper.jpg', 1)
resized_img = cv2.resize(image, (400, 400))
cv2.imshow('Original',image)
cv2.imshow('resized',resized_img)
cv2.waitKey(0)
cv2.destroyAllWindows()

image1=cv2.imread('wallpaper.jpg',1)
roi = image1[50:50 + 425, 50:50 + 425]
cv2.imshow('Cropped Image', roi)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(400,400))
res=cv2.rotate(img,cv2.ROTATE_180)
cv2.imshow('Original',img)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()

img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(400,400))
res=cv2.rotate(img,cv2.ROTATE_90_CLOCKWISE)
# Display the HSV image
cv2.imshow('Original',img)
cv2.imshow('Image Window', res)
cv2.waitKey(0)
cv2.destroyAllWindows()

import cv2
img = cv2.imread("wallpaper.jpg")
img = cv2.resize(img,(300,300))
cv2.imwrite('sipder_man.jpg',img)
```


