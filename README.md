# MobileAudit-SAST-Android
Django application that performs SAST and Malware Analysis for Android APKs

![image](https://github.com/HackWithSumit/MobileAudit-SAST-Android/assets/120317751/8586260f-7565-446b-81b7-3ab476480d5f)


![image](https://github.com/HackWithSumit/MobileAudit-SAST-Android/assets/120317751/be6ad9ea-d759-4d90-9f0a-97287a51f0f1)


<b><h3>Installation</h3>

<b>Using Docker-compose:</b>

Git the Repositories:

     git clone https://github.com/mpast/mobileAudit.git

Enter the Directory:

       cd mobileAudit

Execute all Files:

       chmod +x *

Now install requirements files:

      pip3 install -r requirements.txt

The provided `docker-compose.yml` file allows you to run the app locally in development.

      docker-compose build

      
Then, to start the container, run:    

       docker-compose up

 Optional: run in detached mode (not see the logs)

       sudo docker-compose up -d



