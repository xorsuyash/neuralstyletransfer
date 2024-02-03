# neuralstyletransfer
Neural-Style, or Neural-Transfer, allows you to take an image and reproduce it with a new artistic style. The algorithm takes three images, an input image, a content-image, and a style-image, and changes the input to resemble the content of the content-image and the artistic style of the style-image.
![image](https://github.com/xorsuyash/neuralstyletransfer/assets/98162846/5c80daee-7710-4f5d-8df3-50f06d82506b)

# Architecture 
The principle is simple: we define two distances, one for the content (
D 
C
​
 ) and one for the style (
D 
S
​
 ). 
D 
C
​
  measures how different the content is between two images while 
D 
S
​
  measures how different the style is between two images. Then, we take a third image, the input, and transform it to minimize both its content-distance with the content-image and its style-distance with the style-image. Now we can import the necessary packages and begin the neural transfer.

  ![image](https://github.com/xorsuyash/neuralstyletransfer/assets/98162846/d038f095-e554-41c7-96be-13df92aadea4)

# How to run project 
  install dependencies 

              pip install -r requirements.txt 
  run the app 

              streamlit run streamlit_app.py 
# Link to webapp 
  this we app is deployed on streamlit cloud 
     
  [https://neuralstyletransfer-app.streamlit.app/]

                     
