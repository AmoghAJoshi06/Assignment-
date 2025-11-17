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




    
