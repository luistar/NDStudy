__Running__

Build Dockerfile inside www/ folder by running "docker build . -t test"

Then from parent folder start by running "docker-compose up" 

__Contents__\
Contains two web apps **Addressbook and Claroline**

1. <h3>Addressbook</h3>

        URL: http://localhost/addressbook-mod/addressbook/index.php
        
        credentials :
          username : admin 
          password : admin

2. <h3>Claroline</h3>

        URL:http://localhost/claroline-1.11.10/claroline/install

        Original experiments were done after installing claroline and creating users with following credentials and addition of a course "SE123" under category "science". The setup is available in the VM.
        
        credentials:
          admin
            username : admin
            password : admin


          user
            username : astocco
            password : password
