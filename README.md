
# Linux-Server-configuration
### About
  This Project is about configuring the Linux-Server.

### Server Details

Server IP Address 13.126.138.228

Hosted site Url [http://13.126.138.228.xip.io/](http://13.126.138.228.xip.io/)

### How to connect as grader:

  save private key provided in your local machine and run the following command
  ```
  ssh -i path/to/privatekey -p 2200 grader@13.126.138.228
    
  ```
  
### Id_rsa key
```
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEA4hJjjT7EwfmvSPpdmfsuIqHE1j6ydDwif1UBfQIkBEGU22Yd
C45XXhdDRLqprwS5afHCaBzWNPeFRQZxGGxhrKUftZcwZtSpfnkQqiwZSxSlyGP2
jD5BKWW14DvOMCpuUmoCtA3w6gbUy+cFrINFGwE6W8Y8//f7qYWjMzPVKpsB6rNK
OruVWQ3KW3aOPriS1XvikWhTsgOHFUF9RCpu+n9wFKQv8VlM2LTbrNzyqWBTFZ/K
RbIduDDlgtBxCp209XiG4b56YyG9aDBYjP93OL6BoGkC04w/h/KA8R0s5LWu0mfO
ZllyW0aaaKHkL2rR/xPEVav8Iz9Lsv9PAVqlhQIDAQABAoIBAQDYIVp5i7vR8uJo
c6uO7btyspObe/9h7qfQcjVlDOngA87LXjmAdcoDE1xlVcupnmug5NfGb2M+6jDI
B9uRzPQoeQjys6M7fC660gVjm5tm00uXZDIua8oiSLHzuVlrZPVp5x3Eg9uB8Zv5
gFlFT45+vdLMMJ7a3HsF29RlvDUcb57f5iVCTwuvE4s1wQNVnYDFzmKO0xzaE/ev
q/Otn9Nyhd5oQwzfL0OA9trSrzh/pjDm0lYGEb8kkWuS7jq/aAm1wry7mDSPtY2i
ETElE9vpXsbogCI2NTcuxX4PSDfDa5h9MceQYmmFhpXgpqOg3lMKeQRNBzIB0Kdn
SFXVP3I1AoGBAPdQfJOA8aQh8xUyWcc1LARzH9bpF5PYUOGW4mb+mDCd+vDuPwGB
Y8gvDzXKaz4MXenqWY75e4md/gFKIbqIsqW6FzK94FRQrG55AlJMJyp9nCQ7mAfk
kU6eOJmpvK22LiWKQcCLalDiqAX+Gm77IodypGd6aMq4728WGQWO/tWvAoGBAOoC
6wbKYE9zgTiMcWlqTqAHodng5dopn0ngsfm97Ck2JmU2XXJA7Ag375hJ5exVM5o3
Ooa4ncQnqdvuBKTkBltQ0iyZjaHJ1eeukQxzUU+XFPIZCieo/NKzv8aIET0tEb7D
OeNN6ArKcEGyYIKcqgq3RWCVJqtg3NwtC8IGxLkLAoGBAONmmmV2lrl4je7bkTle
Zs7gnFIbmZZTvGrxNdPGHWH2oRqPtldIBdu3iaDIMrum22OOHDMeqrzrDPdalpDR
yJIh/dqmRHLCiwo5Mi1B4HFtdfjK4wu+2u0TBrAkJl0DuoLCEZtdlbAx+JUqBFwv
hpxMiWasY1ajnWTjSLaXuTH5AoGAbN3Iq1MRNUU+E6m6xVjwlSCX2n33UORWN49y
HQaPTKjleeat2I59gGFNdOLENYt5wz/4WV6f/vaY3jlALdnrXyYdcSRKsL7uZadf
0ZQAeu+Fjg+6GrNSU0/OYzVAF97Ux5OZZbcDwalmShoLLhhmPy/99a3N3KLmfQPz
2WM+t/sCgYBGa6TZFP1Db3DIFQ5FZOO8SJghE5pUdpya5mRuZoWU9M96UO4oww6D
lWSHy2la5aYVj+JHI1+LHYMwAamsRBRTl1g4+0MuhZT6RcRrGOXPLjSozZs6VxR4
3r6wCExGwyBi65b/eID6S/V2uhA5XsdmqKoau9oXSv5NTbkn5L2g8g==
-----END RSA PRIVATE KEY-----
```
### passpharse password
'''
passpharse password is empty(you can directly press enter).

'''
### id_rsa.pub key
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDiEmONPsTB+a9I+l2Z+y4iocTWPrJ0PCJ/VQF9AiQEQZTbZh0LjldeF0NEuqmvBLlp8cJoHNY094VFBnEYbGGspR+1lzBm1Kl+eRCqLBlLFKXIY/aMPkEpZbXgO84wKm5SagK0DfDqBtTL5wWsg0UbATpbxjz/9/uphaMzM9UqmwHqs0o6u5VZDcpbdo4+uJLVe+KRaFOyA4cVQX1EKm76f3AUpC/xWUzYtNus3PKpYFMVn8pFsh24MOWC0HEKnbT1eIbhvnpjIb1oMFiM/3c4voGgaQLTjD+H8oDxHSzkta7SZ85mWXJbRppooeQvatH/E8RVq/wjP0uy/08BWqWF user@vinay
```
### grader password
```
varma
```
### Configuring Linux Server

#### Updating all packages
```
sudo apt-get update
sudo apt-get upgrade
```

#### Creating grader User:
  ```
  sudo adduser grader
  ```
  This will add new user
  ```
  sudo nano /etc/sudoers
  ```
  Below the Root user append the following line
  ```
  grader  ALL=(ALL:ALL) ALL
  ```
  This will grant sudo permission to grader
  #### Creating a ssh key pair for grader
   On your local machine in terminal/command prompt type
   ```
   ssh-keygen
   ```
   Which will generate the public and private ssh keys which is saved to .ssh folder
   
   Then in your virtual machine change to newly created user
   ```
   su - grader
   ```
   Create a new directory .ssh and new file authorized_keys in that directory
   ```
   mkdir .ssh
   sudo nano .ssh/authorized_keys
   ```
   Copy the public key with .pub extension to authorized_keys and save the file
   ```
   chmod 700 .ssh
   chmod 644 .ssh/authorized_keys
   ```
   - 700 will give read write and execute permission to user.
   - 644 prevent other user from writting in to file.
   Then restart ssh server
   ```
   service ssh restart
   ```
   
   Log in to grader with private key generated 
   ```
   ssh -i .ssh/id_rsa grader@ipaddress 
   ```
  #### Changing the ssh port to 2200
   ```
   sudo nano /etc/ssh/sshd_config
   ```
    
   Restart the ssh server
   
   ```
   service ssh restart
   ```
   
   >Note: Before Logging using ssh add custom TCP port 2200 under lightsaail firewall in networking tab in lightsail instance console  
   
   Now Login using command like this
   ```
   ssh -i .ssh/id_rsa -p 2200 grader@youripaddress
   ```
   
  #### Disabling ssh login as root
  `sudo nano /etc/ssh/sshd_config`
  
  make change `PermitRootLogin no`
  
  #### Configurating  Ufw firewall
  ```
  sudo ufw status
  sudo ufw allow 2200/tcp
  sudo ufw allow 80/tcp
  sudo ufw allow 123/udp
  sudo ufw enable
  ```
  This will allow all required ports and enables the ufw
  ```
  sudo ufw status
  ```
  It will display all allowed ports
  
  #### Changing time Zone
  `sudo dpkg-reconfigure tzdata`
  
  select none from list and then select utc.
  
  #### Installing Apache2 
  In terminal 
  
  ```sudo apt-get install apache2```
  
  Now mod_wsgi
  
  ```sudo apt-get install python-setuptools libapache2-mod-wsgi```
  
  Enable mod_wsgi
  
  ```sudo a2enmod wsgi ```
  ##### Setting up your flask application to work with apache2
   Creating a flask app
   
   In /var/www directory create a new folder
   `sudo mkdir FlaskApp`
   
   Install git 
   
   `sudo apt-get install git`
   
   move to the FlaskApp `cd FlaskApp`
   
   In that direcory clone your github repository
   
   `sudo git clone https://github.com/username/catalog.git`
   
   Rename your repository to FlaskApp
   
   Then rename your project file to `__init__.py`
   
   >Error : While accesssing the client_secrets.json file 
   ```
   PROJECT_ROOT = os.path.realpath(os.path.dirname(__file__))
   json_url = os.path.join(PROJECT_ROOT, 'client_secrets.json')
   CLIENT_ID = json.load(open(json_url))['web']['client_id']
   ```
   Use json_url instead client_secrets.json in script
   
  ##### Install and configuring postgresql for project
   Install Postgres `sudo apt-get install postgresql`
   
   login to postgres `sudo su - postgres`
   
   postgres shell `psql`
   
   create user `CREATE USER catalog WITH PASSWORD 'password';`
   
   permit user to createdb `ALTER USER catalog CREATEDB;`
   
   Create a db name  catalog with user catalog `CREATE DATABASE catalog WITH OWNER catalog;`
   
   connect to db `\c catalog`
   
   revoke all permission to public `REVOKE ALL ON SCHEMA public FROM public;`
   
   Give schema permission to user catalog `GRANT ALL ON SCHEMA public TO catalog;`
   
   exit from db and postgres `\q and exit`
   
   Change the database connection in both db_setup.py and `__init__.py` as `engine =       create_engine('postgresql://catalog:password@localhost/catalog')`
   
   Now you are ready with your applicatiom
  #### Configure and Enable a New Virtual Host
   `sudo nano /etc/apache2/sites-available/FlaskApp.conf`
   
   In this add the following code
   ```
   <VirtualHost *:80>
		ServerName mywebsite.com
		ServerAdmin admin@mywebsite.com
		WSGIScriptAlias / /var/www/FlaskApp/flaskapp.wsgi
		<Directory /var/www/FlaskApp/FlaskApp/>
			Order allow,deny
			Allow from all
		</Directory>
		Alias /static /var/www/FlaskApp/FlaskApp/static
		<Directory /var/www/FlaskApp/FlaskApp/static/>
			Order allow,deny
			Allow from all
		</Directory>
		ErrorLog ${APACHE_LOG_DIR}/error.log
		LogLevel warn
		CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>
   ```
   Enable the virtual host 
   `sudo a2ensite FlaskApp`
   
   Disabling the default apache2 page
   `sudo a2dissite 000-default.conf`
   
  #### Create the .wsgi File
    ```
    cd /var/www/FlaskApp
    sudo nano flaskapp.wsgi 
    ```
   Add the following code
   
   ```
   #!/usr/bin/python
    import sys
    import logging
    logging.basicConfig(stream=sys.stderr)
    sys.path.insert(0,"/var/www/FlaskApp/")

    from FlaskApp import app as application
    application.secret_key = 'Add your secret key'
   ```
   save and exit
   
   Deploying flask app with apache2 is referred from [Digital ocean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
   
   #### Installing require modules
   You can either install all modules on your machine or create a virtual environment for the project and install the modules
   ` pip install flask sqlalchemy psycopg2 requests oauth2client`
   
   #### Setting up your Google Oauth2
   Login to your [developer console](https://console.developers.google.com) and select your project and edit OAuth details as following
   
   Javascript origin
   `http://ip.xip.io`
   
   redirect URI
   
   `http://ip.xip.io/login`
   
   `http://ip.xip.io/gconnect`
   
   `http://ip.xip.io/callback`
   
   [xip.io](xip.io) is a free DNS which will be the same as using IP address
   
   #### Final Step
   Restart your apache2 server
   
   `sudo service apache2 restart`
   
