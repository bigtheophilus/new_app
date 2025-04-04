# APPLICATION BUILT TO REMOVE BACKGROUND IMAGES FROM A PICTURE

## The source code was sourced by forking the repo from a public github repo.

##  some adjustments made, some commit to the requirements.txt file because of some of the depenendencies versions where not compatible. 
## for instance rembg can only be compatible with some flask version.


# THE PROCESS:

###  apt-get update
###    1  sudo -i to switch to root user


###    2  apt-get update to update the ubuntu directory


###   3  apt install python3.12-venv -y
![alt text](<images/Screenshot 2025-04-04 020830.png_1.png>)


###    4  git clone https://github.com/bigtheophilus/background-remover-python-app.git
![alt text](<images/Screenshot 2025-04-04 021114.png_2.png>)


###   5  python3 -m venv .venv
###   6  source .venv/bin/activate
![alt text](<images/Screenshot 2025-04-04 021340.png_3.png>)
![alt text](<images/Screenshot 2025-04-04 021531.png_3.png>)



###   7  apt install pip 
![alt text](<images/Screenshot 2025-04-04 021709.png_4.png>)


###    8  pip --version

![alt text](<images/Screenshot 2025-04-04 022018.png_5.png>)



###    9  cd background-remover-python-app/
###    10 python3 -m pip install -r requirements.txt



###    11 cat app.py 
###    12 nano requirements.txt
###    13 python3 -m pip install -r requirements.txt

![alt text](<images/Screenshot 2025-04-04 022630.png_6.png>)
![alt text](<images/Screenshot 2025-04-04 022742.png_6.1.png>)


###    14 pip install onnxruntime

![alt text](<images/Screenshot 2025-04-04 023046.png_7.png>)


###    15 python3 app.py

![alt text](<images/Screenshot 2025-04-04 023450.png_8.png>)

## ISSUES

### On the reqirement.txt, onnxruntime was not stated and its a requeirment for the application to run . adding the onnxruntime to the requirments.txt and tried to install or compile the requirment componets returned with a failure. hence i commented it out and re run it and all the dependencies install and soly used pip to install onnxruntime and then the application ran succesfully.

## image: 
![alt text](<images/Screenshot 2025-04-04 023812.png_9.png>)



   
   


   
   
   
   
   
   
   
   
   
   
   
