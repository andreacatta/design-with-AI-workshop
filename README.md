# design-with-AI-workshop
latest update: 2021 September the 28th

## Step 1 - get Arduino IDE
1. go to https://www.arduino.cc/en/software and download the IDE
2. open the .zip file and check out this guide for detailed installation instructions https://www.arduino.cc/en/Guide

![immagine](https://user-images.githubusercontent.com/6803317/135173494-d52e390e-08cb-4e01-99aa-d60db68c8885.png)


## Step 2 - get Processing and install libraries
1. go to https://processing.org/download and download stable version 3.5.4

![immagine](https://user-images.githubusercontent.com/6803317/135172656-92ffb855-395e-413d-aaee-0ca480ccca84.png)

2. open the .zip file and move the content to your applications folder
3. launch Processing app (or Processing.exe in Windows)
4. go to Sketch > Import Library.. > Add Library

![immagine](https://user-images.githubusercontent.com/6803317/135177835-44d39bd0-37c1-4e9b-b53d-f449c72e3ad9.png)

5. search for ControlP5 library and install it (look down-right for install button)
6. search for Websockets library and install it
7. close the window


## Step 3 - download this repo
1. download this repository

![immagine](https://user-images.githubusercontent.com/6803317/135174303-37e48247-d34e-4518-a606-3b0566895749.png)

## Step 4 - move arduino libraries
1. unzip the archive
2. copy the content of "arduino libraries" folder
3. open Arduino IDE and open Preferences panel
4. look at your library folder location
5. 
![immagine](https://user-images.githubusercontent.com/6803317/135174563-0f5e1ece-90a8-4615-bd6c-f3df334f83db.png)

4. go there in Finder or File Explorer and paste here folders from "arduino libraries" 

## Step 5 - setup the board
1. assemble the Arduino Arduino BLE 33 Nano and camera on the shield as shown here

![immagine](https://user-images.githubusercontent.com/6803317/135175194-c4487bdf-83a2-42ea-af6f-8ad975cc7b56.png)

2. connect the USB cable to your computer

## Step 6 - setup Arduino IDE
1. open Arduino IDE
2. a small banner at the bottom of the sketch windows should appear

![immagine](https://user-images.githubusercontent.com/6803317/135175459-5e3af2f3-8feb-406d-94b9-9d3ce1d1b391.png)


3. click there to open the board core library installer
4. move the mouse over the window and click over Install

![immagine](https://user-images.githubusercontent.com/6803317/135175643-9597f47a-6c05-49a8-94c1-0580d2f06590.png)

5. close the windows
6. from menu Tools > Board > select our  Arduino BLE 33 Nano 

![immagine](https://user-images.githubusercontent.com/6803317/135176869-66625fc6-375e-4caa-a56f-93ba82412524.png)

7. close and re-open Arduino IDE and select the port

![immagine](https://user-images.githubusercontent.com/6803317/135177064-99cd9204-0792-447c-8f16-ffa201138930.png)

## Step 7 - launch Arduino uploader
1. open the folder you downloaded from the repo
2. open the sketch /tiny_image/tiny_templates/TMUploader/TM_Uploader/**TM_Uploader.ino** in Arduino IDE
3. upload to the board

![immagine](https://user-images.githubusercontent.com/6803317/135177310-28d9a780-210c-4ad7-9db9-988b322ebc93.png)


## Step 8 - launch Processing connector
1. open the folder you downloaded from the repo
2. open the file tiny_image/tiny_templates/TMConnector/TM_Connector/**TM_Connector.pde** in processing 
3. click on "play" button to run the script. A smll window should pop-up

![immagine](https://user-images.githubusercontent.com/6803317/135178220-65eee97e-c0be-42b9-8a11-89a698d1da95.png)

5. now go to Arduino IDE and look for the port name from Tools menu
6. go back to the Processing pop-up window, click on the blue button and select the same port as in Arduino IDE

![immagine](https://user-images.githubusercontent.com/6803317/135178386-408ad43e-f66a-48e9-8685-9061f78559d2.png)

the left side of the window should now show your Arduino camera view





 
