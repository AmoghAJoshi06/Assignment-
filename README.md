#  Devops Assignment

Task 01 : To create a web page. 

   Steps are followed for this 

    Step 1 : Create a Instance for this from the AWS EC2 and connect with SSH  
    Step 2 : After connecting with SSH do update the system by updating the system by using the command **" sudo apt-get update"**
    Step 3: For the backend I am using Python with the flask to do the web page backend. 
    Step 4: For runing the SSH go to folder where we have saved the key to create the instance and loacte it come back to instance and click on coonect then go to the SSH client there we will get the link like this** " ssh -i "Devops.pem" ubuntu@ec2-16-171-64-192.eu-north-1.compute.amazonaws.com"**. 
    Step 5: Copy the link and Paste in the command Terminal where the key is locate after we get the ubuntu server in it 
    Step 6: Again i have checked for any updates and I have start to install mu Python and with its Pip version in my ubuntu setup
    Step 7: I have used the command sudo apt update, **"sudo apt install python3 python3-pip -y"** i have done in ame time I have updated and installed the python wit its pip
    Step 8: After the installing the Python and Pip i have check the version of the Pip by commmand pip3 --version
    Step 9: After that I have Installed Flask into it by command **"pip install flask"** 
    Step 10: After that write the command nano app.py where it create the small file to write the code for the webpage 
    Step 11: After that writing the come back by using crlt+o to save and crlt + x to exit 
    Step 12 : Open a new tab in the tab open Your web page like this **"http:// Public IP address: 5000" and you can see your output**
    
Problems That when doing this 
    1. we can't directly download the flask directly after installing the python in the ubuntu, As we have to cerate a env to do it the command i used to do the env for my server was 
    First install the env the command : **"sudo apt install python3-venv -y"**
    Second create that env in the ubuntu command : **"python3 -m venv myenv"**
    Next activate that env command : **"source myenv/bin/activate"**
    Aftr that we can install the flask 
    For the decative the env command : **"deactivate"**

 


