## How to: transfer files to/from remote machine (MobaXterm)

#### Step 1:  
Make sure you are connected to the internet, then launch the MobaXterm application and log on to the remote machine. If you are unsure about anything mentioned in this step, please reference the previous tutorials, [How to: Install MobaXterm](installMobaXtermWindows.md) and/or [How to: Remote Login using MobaXterm](remoteLoginMobaXtermWindows.md)  
  
The following screenshot shows my username “cking74” currently logged on to the storm servers. You should see something similar before continuing on to the next step.   
  
![Logged in screen](docs/assets/CISWork17.png)  
  
  
#### Step 2:  
Using MobaXterm, you can easily view and access the remote machine using the window to the left of the terminal. You can see its current location displayed in the top bar and navigate through the machine by clicking on the folders as shown in the screenshot below.  
  
![Navigate the remote machine](docs/assets/CISWork18.png) 
  
In the above example, I have just logged into the remote machine, so the folder I am currently accessing is **/home/students/cking74** which contains the directories **private, public_html, demo, example** as circled, other files and a **green arrow button** which I can use to go back a directory.  
  
You can also navigate the machine via the command-line in the window to the right and see the changes reflected in the folder to the left if you check the **Follow terminal folder** box.   
  
![Follow terminal folder](docs/assets/CISWork19.png)  
  
The following example shows me navigating to **/demo/text_files** via the command-line using the **pwd**, **cd** and **ls** commands, with the window on the left adjusting itself accordingly. (Don’t worry if you are not yet familiar with these commands, they are covered further in the **Introduction to Linux** tutorial.)   
  
![Navigate to /demo/text_files](docs/assets/CISWork20.png)  
  
  
#### Step 3:  
To download a file on to your local machine, first locate and select the file on the remote machine that you wish to download using one of the methods explained in the above step. In this example I will be downloading the folder “data” from the location in the remote machine which I navigated to in the previous step. (To download a file or folder is the same process.)   
  
![Download the folder “data” from the remote machine](docs/assets/CISWork21.png)  
  
Next, click on the blue download arrow. A window displaying your local machine will pop up prompting you to select the location where you wish to download the files. After doing so, click the **OK** button to confirm the download.  
  
![Download and select location](docs/assets/CISWork22.png)  
  
Then you should see the files appear on your local computer. We can now see the “data” folder exists in the “Documents” folder in the example below.   
  
![“data” folder in the “Documents” folder](docs/assets/CISWork23.png)  
  
  
#### Step 4:  
To upload a file to the remote machine from your local machine is a very similar process.  In this example, I will be uploading an image from the folder “Screenshots” from my local computer to the remote machine.  
  
![“Screenshots” folder on local computer](docs/assets/CISWork24.png)  
   
I will upload it to the folder where I am currently located on the remote machine named “text_files” First, I will click the green **upload** button which will bring up a window of my local computer. I will navigate to the “Screenshots” folder through this window, open it and select the screenshot to upload. Then I will click **open**.  
  
![Select screenshot from folder to upload](docs/assets/CISWork25.png)  
  
After this, you can now see the image, “Screenshot (1) has been transferred to the remote machine as shown below.   
  
![Screenshot transferred to the remote machine](docs/assets/CISWork26.png)  
  
  
#### Step 5:  
Documents can also be exchanged between the local and remote machines by simply clicking-and-dragging.  In the following screenshot, you can see the results of me clicking and dragging the file “info.txt” from the remote machine into the Documents folder of my local computer.  Similarly, files can be dragged from the local machine into the remote machine.  
  
![Document clicked and dragged to local computer](docs/assets/CISWork27.png)  
  
**Congratulations!** You can now transfer files between a local and remote machine using MobaXterm! 