# Minehub Project (IT)

Back-end Link: https://github.com/albedim/Minehub-BE<br>
Fron-end Link: https://github.com/albedim/Minehub-FE

This is an open source project that you can configure as you want in order to make the website for your minecraft server.
Everything is configurable, **change**, **try** & **enjoy**!

# How to start?

It's really simple, these are the steps you need to follow.
The project is made with React JS, MySQL & Python 3.10.
I know that better frameworks exist for back-end but i decided to use Flask & python because you can deploy easier

- This is the front-end link. Download it: https://github.com/albedim/Minehub-FE

- Open the folder you have just downloaded and run the terminal. Run this command:
  > npm install

- Go in "src" folder and open config.js. You need to change these information in order to personalize the website!
  > export const SERVER_NAME = "Server name"<br>
  > export const DESCRIPTION = "Server description"<br>
  > export const COLORS = ["#d880d9", "#9c2b88", "#9d2b88","#d164bd", "#d173bf"] # Color codes<br>
  > export const DISCORD = "Discord link of the server"<br>
  > export const INSTAGRAM = "Instagram link of the server"<br>
  > export const SERVER_IP = "Server Ip"<br>
  
- Now you need to download the back-end, this is the link: https://github.com/albedim/Minehub-BE
  
- Open the folder you have just downloaded and run the terminal. Run this commands:
  > python -m venv env<br>
  > cd env/Scripts<br>
  > activate<br>
  > python install -r requirements.txt
  
- Go in "resources". Open config.py You need to change these information in order to set the database credentials!
  > config = {<br>
  >  "host": "DATABSE HOST",<br>
  >  "username": "DATABASE USERNAME",<br>
  >  "db-name": "DATABASE NAME",<br>
  >  "password": "DATABASE PASSWORD"<br>
  >}
  
- Now go in "resources" again and open rest_service.py You need to change these information in order to create your admin credentials!
  >  "admin": {<br>
  >    "username": "CREATE AN USERNAME",<br>
  >    "password": "CREATE A PASSWORD",<br>
  >}
  
- Now open app.py and change the last line. "host" is going to be the iP address of your machine. "port" is going to be the port you want to host the application on

- Now open the terminal and run this command: python app.py. If everything was made correctly it should print "Yuor application is running on IP ADDRESS"

- Go in the front-end folder and open config.js. You need to change these information in order to connect the back-end!
  > export const BACKEND = "http://IP_ADDRESS:PORT/api/v_1_9_0"<br>
  
- Now open the terminal and run this command: "npm start".

- The application should open and work fine. For any problem you may face, contact me on telegram https://t.me/albedim or send me an email to dimaio.albe@gmail.com
  


  

