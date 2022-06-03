# Age-and-Gender-Classifier

This project was done as part of Major Project for B.Tech

We first do a comparitive analysis of 3 models namely-
1) Resnet
2) VGG
3) Sequential CNN (CNN built on our own)

We found that the sequential CNN had better accuracy compared to Resnet and VGG , hence we did a real time implementation of the sequential CNN.

To run this project -

Download all files from this repo and this google drive link => https://drive.google.com/drive/folders/1V2YrqbJiRzwESyg3mSOXuLFiHu-aY5O6?usp=sharing
Upload the ipynb files on to Google Colab , change the runtime environment to GPU (you can do this by Runtime-> Change Runtime) for faster processing.
Upload the .csv file onto your google drive
Change the directory path in the code as per where the .csv file has been uploaded in your drive.
Run the code

If you find that sequential CNN to perform better then you can implement the realtime

First download the UTK face dataset from this link - https://susanqq.github.io/UTKFace/
Change the directory address in the code
Run train.py (training can take from few hrs to days based on your computer specs)
On successfully getting your age and gender model , run run.py , the camera/webcam will turn on and will be able to use input from the camera to detect the age and gender
