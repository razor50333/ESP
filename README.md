# SharedESP
Shares the ESP between the users of this LUA

![](stuff/showcase.gif)

## Setting up a server

### For Windows
- Port forward the port 57020 (UDP)
- Download and install [NodeJS](https://nodejs.org/en/) on your system
- Download the server script (server.js)
- Open a terminal (cmd, PowerShell, etc)
- Navigate to the path where the server script is downloaded
- Run the server script with "node server.js"

### For Linux
Run these commands in super user mode

    apt install nodejs
    ufw allow 57020
    ufw allow ssh
    git clone https://github.com/razor50333/ESP
    cd ESP
    node server.js
    

## If you want your server to be added to the server list
PM me on the AIMWARE forum or discord (panicbutton#5807) with the server IP and it's location
