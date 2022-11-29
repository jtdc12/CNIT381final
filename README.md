# CNIT381final
Build a Network Management Chatbot that has the following:

◦ At least 1 Paramiko/Netmiko skill.

◦ At least 1 NETCONF/RESCONF skill.

◦ At least 1 Ansible skill.

◦ A monitor (described in attachment).

This repository will also help setup the bot to run it on your machine. 

Prerequisites: 

◦ Linux Environment

◦ Visual Studio Code

◦ Webex Credentials

◦ Ngrok Web Hook

◦ Bot Credentials

Step 1: Download all the needed files into a directory that can be accessed by VS Code

Step 2: Make an account on https://developer.webex.com/

Step 3: Make a bot, write down all informaion showed in screenshot for use later
![image](https://user-images.githubusercontent.com/8886770/201720281-156a2728-1e4e-4d45-8749-473623d5f824.png)


Step 4:A Web Hook using Ngrok: For the bot to be able to send and receive messages through Webex Teams. the command to get your webhook is ngrok http 5000 in terminal 

Step 5: To make your chatbot.py file work, you will need to fill out the bot_email, teams_token, and bot_url fields. These fields will be filled in with your Email, Webex Access Token, and Webhook address. Next, in the useless_skills.py, put the Teams Access Token in the teams_token field. 

Fields to Fill in chatbot.py
![image](https://user-images.githubusercontent.com/110984023/204409795-42f51726-6e07-4342-8708-230738a25daa.png)


Fields to Fill in useless_skills.py


Step 6: Update the routers.py file with your routers IP address.

Step 7: In VS Code, open a terminal for your directory you created and run the command python3 chatbot.py, this should run the bot in the terminal. 

Step 8: Open Webex and begin chatting!
