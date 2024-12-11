# Bikelane_Detector

This repository contains data and notebooks used to detect objects that are blocking bike lanes, primarily vehicles. Below is a structure of the directory

Ignore all Demo files (used to make the folders/branches)

Method 1

  --- data 
  
     --- data (Folder of data for single security camera footage)
     
       --- blocked2 (Folder of blocked bicycle lane images)
       
       --- notblocked2 (Folder of unblocked bicycle lane images)

     --- data2 (Folder of data for all security camera footage)

       --- blocked3 (Folder of blocked bicycle lane images)

       --- notblocked3 (Folder of unblocked bicycle lange images)

      --- data3 (Folder of data for YOLOv8 model on all security camera footage)

        --- images (Images used in the YOLOv8 model

          --- train (Images used in the training)

          --- val (Images used in the validation)

        --- labels (Labels corresponding to the bounds of vehicles blocking the bicycle lane within the images

          --- train (Labels used in training)

          --- val (Images used in the validation)
      
      
  
  --- notebooks - Contains all of the notebooks of code utilized in method 1 (Security Camera footage)
  
     --- MultipleCams.ipynb - Contains the code used for the second analysis (all security camera footage)
     
     --- SingleCam.ipynb - Contains the code used for the first analysis (single security camera footage)
     
     --- YOLOV8-Annotated.ipynb - Contains the code used for the third analysis (YOLOV8 model on all security camera footage)

Method 2

  --- Bikelanes
  
    --- blocked (folder of blocked images from previous method)
    
    --- unblocked (folder of unblocked images from previous method)
    
  --- NEW
  
    --- BLOCKED_NEW (folder of blocked FPV images)
    
    --- UNBLOCKED_NEW (folder of unblocked FPV images)
    
  --- FPV.ipynb (python notebook that trains last method's model, tests that model on FPV data, and trains FPV model)
  
  --- yolov8n.pt (yolo checkpoint for refined model)
  

