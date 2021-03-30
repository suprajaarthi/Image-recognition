# Image-recognition
Image recognition in Tensorflow 

https://colab.research.google.com/drive/1TXUjLJ38Xt7hX-U5aap6aFnxLBu5AWsk

https://commons.wikimedia.org/wiki/Main_Page
  - Search image with tags
  - Select Use this file option
  - Copy file URL
  - https://upload.wikimedia.org/wikipedia/commons/6/69/June_odd-eyed-cat_cropped.jpg

<b>References :</b> 

- https://tfhub.dev/tensorflow/collections/object_detection/1

- https://colab.research.google.com/github/tensorflow/hub/blob/master/examples/colab/object_detection.ipynb

# OCR - Image Preprocessing 
Pillow, Tesseract , Kraken and OpenCV for Image preprocessing and Optical Character Recognition 
<hr>
To upload image using Drive : 

```python
from google.colab import drive
drive.mount('/content/drive')
#Mounted at /content/drive
file = files.upload()
# image=Image.open(file)
# print(file)
image=Image.open('/content/drive/My Drive/dawn.jpg')
print(image)
```
