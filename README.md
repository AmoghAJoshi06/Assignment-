#  Devops Assignment

Task 01 : To create a web page. 

   Steps are followed for this 

    Step1: Create a new instance in EC2 system and connect with the SSH system in your PC by locating the Key of that instance open the terminal where the key is present and paste this **"ssh -i "Devops.pem" ubuntu@ec2-13-49-245-252.eu-north-1.compute.amazonaws.com"**
    Step 2: Ater that the ubuntu will be showed then check for the update in by **"sudo apt-get update"**
    Step 3: Afetr the updation her i am using the python for my backend of my web development download the Python into it by the command **"sudo apt install python3 python3-pip-y"**
    Step 4: After installing check for the pip version by using **"pip3 --version"**
    Step 5: Next download the flask version into it command **"pip install flask"**
    Step 4: Create a file by using the vim like i have used **vim backend.py**
    Step 5: After writing the code in the backend.py check it by using **"python3 backend.py"**
    Step 6: Next come to the Frontend of the web page here make a another file as index.html command: **"vim index.html"**
    Step 7: In that write the HTML code for the program and run it by using **"python3 -m http.server 8080"**
    Step 8: And then check in the web page wheather programming is running in your public id 

Problem Faced in this.

     First you have to make sure everytime who check wheather I have python and pip in it 
     Next is that we can't run the flask directly into it as we have to create a new environment to it and then download the flask in it or it will give error 
     To create the environment is **"sudo apt install -y python3-venv python3-full"** to crate **"python3 -m venv venv"** and to activate it **"source venv/bin/activate"** at last to deactivate use the same command **"deactivate"**


Task 02: Dockerize Both Components
 * Write a Dockerfile for the backend
 * Write a Dockerfile for the frontend.
 * Write a docker-compose.yml that:
     -Runs both containers
     -Frontend on port 8080
     -Backend on port 5000
     -Frontend calls backend using service name (not localhost)

Steps are followed for this 

    Step 1: Create a instance for the docker 
    Step 2: Next update the instance - "sudo apt update"
    Step 3: exit the instance and again login to it
    Step 4: Next install Docker file - 
    **sudo apt install -y docker.io
    sudo systemctl enable docker
    sudo systemctl start docker
    sudo usermod -aG docker ubuntu**
    Step 5: Next install docker compose **sudo apt install -y docker-compose**
    Step 6: Create the directory as project next go to into that directory and create a another directory into it backend and frontend
    Step 7: Create the backend called as app.py - **vim backend/app.py** and write the code save and exit
    Step 8: Create a requrinmentfor the backend that is the flask : **vim backend/ requriment.py**
    Step 9: Next create a backend Dockerfile to it - **vim backend/Dockerfile**
    Step 10: After the backend is done come to the frontend part of the docker file 
    Step 11: For the frontend i have used as index.html : **vim frontend/index.html** . In that write the code and save and exit from it
    Step 12: Next create a Dockerfile for it - **vim frontend/Dockerfile**

Problems 

    I could write the backend full script for the docker file 
    I have written only few line of the front of the index.html
    I could written the frontend Docker-file 
    I got the errors when downloding the Docker-File into my system 


Task 03: Deploy on AWS EC2
 * Launch a t2.micro Ubuntu EC2 instance.
 * Install Docker and Docker Compose
 * Clone your project and run using docker-compose.
 * Open port 8080 in the security group
 * Verify
     - Frontend loads in browser
     - Backend works through the frontend


   Step are followed

       Step 1: Create a instance by using EC2
       Step 2: In the instance link to the ubuntu server and in that downloaded Docker into
       
    



    
