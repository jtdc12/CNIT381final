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

Step 3: To make your 381Bot.py file work, you will need to fill out the bot_email, teams_token, and bot_url fields. These fields will be filled in with your Email, Webex Access Token, and Webhook address. Next, in the useless_skills.py, put the Teams Access Token in the teams_token field. 

Fields to Fill in 381Bot.py


Fields to Fill in useless_skills.py


Step 4: Update the routers.py file with your routers IP address.

Step 5: In VS Code, open a terminal for your directory you created and run the command python3 381Bot.py, this should run the bot in the terminal. 

Step 6: Open Webex and begin chatting!
