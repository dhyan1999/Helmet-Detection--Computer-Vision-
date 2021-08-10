<p align="center">
  <a href="https://github.com/dhyan1999/Helmet-Detection--Computer-Vision-" title="Helmet Detection">
  </a>
</p>
<h1 align="center">🪖 Helmet Detection 🪖</h1>
<p align="center">2021G COMP-5112-GDF - Research Methodolody Computer Science</p>



<h2 align="center">🌐 Links 🌐</h2>
<p align="center">
    <a href="https://youtu.be/ud4P45zhCk0" title="Helmet Detection">🖥️ Video</a>
    ·
    <a href="https://github.com/dhyan1999/Helmet-Detection--Computer-Vision-" title="Helmet Detection">📂 Repo</a>
    ·
    <a href="https://github.com/dhyan1999/Helmet-Detection--Computer-Vision-" title="Helmet Detection">📄 Paper</a>
</p>

## Table of Content

1. [Manifest](#-manifest)
2. [Prerequisites](#-prerequisites)
3. [Installation Steps](#%EF%B8%8F-installation-steps)
4. [Installation of important Libraries](#-installation-of-important-libraries)
5. [Installation of labelImg](#installation-of-labelImg)
6. [Use of labelImg in the project](#Use-of-labelImg-in-the-project)
7. [Necessary Things for a README](#necessary-things-for-a-readme)

## 🧑🏻‍🏫 Manifest

```
- bike.ipynb --> A python file that run's Helmet-Detection code
- bike.xml   --> A xml file which has the entries of all the co-ordinates of each 
                 image(in the image folder) and has been trained on detecting two classes 
                      1. Helmet
                      2. No Helmet
- README.md ---> This markdown file you are reading.
- Image ----> Image folder has all the images of people wearing and not wearing Helmet
- movie2.mp4 --> These is the movie file on which we are going to run our Helmet-Detection
                 model
                 (Anybody can change these movie file and put there's file for testing😀)
```


## 🤔 Prerequisites

- [Python](https://www.python.org/ "Python") Installed

- Python Basics Understanding

- [OpenCV](https://pypi.org/project/opencv-python/ "OpenCV") Library Installed 

- Computer Vision Basic Understanding

## 🛠️ Installation Steps

1. Install [Anaconda](https://www.anaconda.com/products/individual "Anaconda") Software

2. Click on Juypter Notebook

3. Create a seperate folder of any name you want

4. Upload 3 files there bike.ipynb, movie2.mp4 and bike.xml in that folder

5. Run bike.ipynb

**🎇 You are Ready to Go!**

## ❗ Installation of Important Libraries

Before running the .ipynb file we need to import some of the libraries using terminal 

In the Anaconda Terminal, you can run:

```Bash
pip install opencv-python
```

For installing TKinter (If it shows the error that Tkinter is not installed)

```Bash
pip install python-tk
```

## Installation of labelImg

- LabelImg - LabelImg is a free, open source tool for graphically labeling images. It’s written in Python and uses QT for its graphical interface. It’s an easy, free way to label a few hundred images 
- Installation steps as in command prompt.

## Use of labelImg in the project 

- Step1 - Write the command labelImg in the command prompt which will open a window as shown below.
- Step2 - Open the directory where all the pictures are saved using the open directory link available on the left hand side.    This step will display all the images on right side small window.
- Step3 - Make sure YOLO is selected. Then, select the first picture and choose the command create rectBox. On clicking on rectBox, a rectangle can be drawn around the face of the person. 
- Step4 - In this step, we will create a rectangle box around the person and give it a name depending on whether the person is wearing the helmet or not. If the person is wearing a helmet, class name is given as helmet and if not then the class name is given as no helmet. Now we will save this picture.
- Step5 - Now after saving the picture, a class file and a txt file is formed in the folder. Class file contains the 2 classes (helmet and no helmet) that we made and the txt file contains the coordinates of the rectangle that we made around the person’s face.
- Step6 - Step’s 3, 4 and 5 are repeated for the rest of the pictures. It’s important to note that, for every picture the class file will remain same but different txt files will be made. 
- Step7 - So, finally after saving the changes made to the last picture one can see 1 class file and different txt files in the folder. 
- Step8 - We will combine all these txt files into one file known as the bike.xml file and we will use this xml file in our code to detect the person wearing helmet.


## 📂 Directory Structure

> [`create.bat`](https://github.com/king-technologies/Project-Initiator/blob/main/create.bat "Create Command"): Command file that will execute the python file

> [`remote.py`](https://github.com/king-technologies/Project-Initiator/blob/main/remote.py "Main File"): Python file, the main file that contains the script

## 🎊 Future Updates

- [ ] Add project boilerplate automatically for different languages and frameworks

- [ ] Add GUI

- [ ] Add Other VCS

## 🧑🏻 Author

**Rohit Jain**

- 🌌 [Profile](https://github.com/Rohit19060 "Rohit Jain")

- 🏮 [Email](mailto:rohitjain19060@gmail.com?subject=Hi%20from%20Project%20Initiator "Hi!")

- 🦁 [Website](https://kingtechnologies.in "Welcome")

<h2 align="center">🤝 Support</h2>

<h3 align="center">🎀 Contributions (<a href="https://guides.github.com/introduction/flow" title="GitHub flow">GitHub Flow</a>), 🔥 issues, and 🥮 feature requests are most welcome!</h3>

<h3 align="center">💙 If you like this project, Give it a ⭐ and Share it with friends!</h3>
<h3 align="center">💰 Donations Links</h3>
<p align="center">
<a href="https://www.paypal.me/kingrohitJ" title="PayPal"><img src="https://kingtechnologies.in/assets/images/Paypal.png" alt="PayPal"/></a>
<a href="https://www.buymeacoffee.com/rohitjain" title="Buy me a Coffee"><img src="https://kingtechnologies.in/assets/images/Coffee.png" alt="Buy me a Coffee"/></a>
<a href="https://ko-fi.com/rohitjain" title="Ko-fi"><img src="https://kingtechnologies.in/assets/images/Kofi.png" alt="Ko-fi"/></a>
<a href="https://www.patreon.com/KingTechnologies" title="Patreon"><img src="https://kingtechnologies.in/assets/images/Patreon.png" alt="Patreon"/></a>
</p>

<p align="center">Made with Python & ❤️ in India</p>

# helmetdetection
Helmet Detection With GUI in python tkinter.

I created Graphical user Interface in Phase 1.

Now in Phase 2:
I created a script to detect bike on video footage.
But that is not yet integrated in GUI part.

I am still making algorithm for helmet detection.

I will update the code and upload it as soon as the beta test is completed.

Thank You.