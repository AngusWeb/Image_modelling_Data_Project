# Data Analytics Project: Warframe Trade Chat

I have written a notebook **'Imaging_Modelling_Project_Notebook.ipynb'** that provides an explanation of the current version of my program, which is my first image modelling project. 
I chose a unique project that interests me, aiming to use Python to control the computer and extract data from a video game's 'trade chat'.

## Project Aim
The primary objective of this project was to use PyAutoGUI to control the keyboard and mouse, while using OCR and modelling methods enabling the program to:
1. Select links using detection techniques
2. Gather data based on the links' locations,appearence and contents
3. Enter the collected data into a Pandas DataFrame for further analysis

Additionally, the program is designed to flag and notify the user about important data points.

## Inspiration
The inspiration for this idea came from a popular service called Playwright.dev which automates actions on certain websites/apps like uber. However, I am applying it to the video game 'Warframe'.

## Evolution of the Project
- **Version 1**: Used Pytesseract (Google's Tesseract-OCR Engine) and cv2 template matching. Later tried colour matching.
- **Current Version**: Switched to EasyOCR and YOLOv8, finding them far superior despite the initial setup required for YOLO.
  
## Lessons Learned
- While training models can be tedious, using pre-built, well-designed models like YOLOv8 makes them very useful and powerful.
- Modelling is computationally intensive, so it's important to use models at breakpoints in the program where pauses are less impactful.
- Machine learning alternatives like EasyOCR significantly outperformed Tesseract (in my use case), which uses a set of techniques for OCR.




## Image Examples
Here are some image examples of OCR and model detection used by my program.
![Yolov8 model detection](https://i.imgur.com/Yjuoldj.png)
![OCR screen 1 using EASY OCR, targetting white boxes](https://i.imgur.com/7ctzfhE.png)
![OCR screen 2 using EASY OCR](https://i.imgur.com/SQSw1LY.png)



