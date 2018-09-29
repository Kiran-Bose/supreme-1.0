# supreme
Supreme is a command line file manager written in shell script.

Supreme helps you open,copy,move,delete,rename files from phone(android),usb drive,cloud storage and local drive(Tested for ubuntu 18.04).

Download the deb package to any debian based system and install

Supreme(V1.1.22) uses package 'rclone'(1.42) for cloud storage operations.

    If the rclone package installed by deb installer automatically is a lower version, 
    download the rclone deb package included in this repository and install or 
    visit below link to download latest version.
  https://rclone.org/downloads/ 

You may also add it from PPA:
For bionic and xenial, do the following:

    sudo add-apt-repository ppa:kiran.kb/supreme
    sudo apt-get update
    sudo apt-get install supreme
    
For other ubuntu versions, this PPA can be added to your system manually by copying the lines below and adding them to your system's software sources.

    deb http://ppa.launchpad.net/kiran.kb/supreme/ubuntu bionic main 
    deb-src http://ppa.launchpad.net/kiran.kb/supreme/ubuntu bionic main

Usage: Type 'supreme' and hit enter in the bash terminal. Follow the instructions

Functionality overview

(1)Open Apps  


    ----Firefox                                  
    ----Calculator          
    ----Settings               
    
(2)Manage Files   


    ----Search                        
    ----Navigate                
    ----Quick access         
    
                    |----Select File(s)
                    |----Inverse Selection
                    |----Make directory
                    |----Make file
                                                  |----Open
                                                  |----Copy
                                                  |----Move
                                                  |----Delete
                                                  |----Rename
                                                  |----Send to Device
                                                  |----Upload to cloud
                                                  |----Properties

(3)Manage Phone    


    ----Move/Copy from phone          
    ----Move/Copy to phone            
    ----Sync folders                          
    
(4)Manage USB 


    ----Move/Copy from USB        
    ----Move/Copy to USB  
  
 (5)Manage Cloud
 
    ----Upload to cloud
    ----Download from cloud
    ----Delete from cloud
    ----Move/copy cloud resource
    
