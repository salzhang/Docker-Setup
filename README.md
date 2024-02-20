# Docker-Setup
### Step 1: Pull latest image 
First, run the following code inside your commind line window: `docker pull cis5710/hw-base:latest`
    
Then, run the following code inside your command line window: `docker run -it cis5710/hw-base:latest /bin/bash`.

After that, open Docker Desktop and you will see a new running container.

### Step 2: Create ssh key and add it to your account 
First, open VSCode to connect to the new container. You can click the down left button, and select ***Attach to Running Container***.
    
***Show-Change Marker Data:***    *Alt+M*   
Once you click this option, a window allowing you to control the ___location & name___ of the marker would show up. You can enter the ___specific time___ you want to monitor on ___the left column___ and you can ___rename the marker___ by putting words into ___the right column___ to replace their default name.   

***Drop Named Markers:***    *Alt+N*   
Once you click this option, a named marker will be dropped at the current position of your primary marker. If you then move your primary marker away, the named marker will still stay at that marked position.   

***Collect Named Markers:***    *Shift+Alt+N*   
Once you hover your primary marker on a named marker and click this option, the named marker will be collected.   

***Collect All Named Markers:***    *Shift+Ctrl+Alt+N*   
Once you click this option, all named marker will be collected.   

***Copy Primary->B Markers:***    *B*   
Once you hover your primary marker on a position and click this option, a ___Base Marker___ will be added. Then when you move away your primary marker, the location of the base marker and the deviation of your primary marker from the base marker will be shown on the panel.  

### Function 3: Simple Edit Functions 
***Highlight All:***    *Ctr+A*

***Insert Blank Row:***    *Ctr+B*      

***Copy:***    *Ctrl+C*    
