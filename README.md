#Before executing this handson ensure you have connected to you server

#Run all the scripts with sudo permissions

#Here Ubunutu-Server is used at the time of demonstrating this project

#STEP 1 : The pyHttpServer.py must be in the /home/{user}/ directory 

#STEP 2 : Run the set_Unit_Sections. this will set up a new unit file at /etc/systemd/system/pyserverd.service

#STEP 3 : Run the configure_systemd_daemon . this will configute the deamon status to enable the pyserverd.service

#STEP 4 : In case of using a VIRTUAL BOX to run the server change the network settings of virtual-box-server from NAT to BrigedAdapter
then get your server ip and then open you host browser and seach for server-ip : 8000 . [ex : 192.76.34.137:8000]

# To Stop your running daemon service of the pyserverd.service use commands like 

#sudo systemctl stop pyserverd.service -- from preventing current execution
#sudo systemctl disable pyserverd.service -- to disable execution from boot-loading

#And then use sudo systemctl daemon-realod
