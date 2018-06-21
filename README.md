
# Linux-Server-438
### About
  This Project is about configuring the Linux-Server.

### Server Details

Server IP Address 13.126.183.95

Hosted site Url [http://13.126.183.95.xip.io/](http://13.126.183.95.xip.io/)

### How to connect as grader:

  save private key provided in your local machine and run the following command
  ```
  ssh -i path/to/privatekey -p 2200 grader@13.126.183.95
    
  ```
  
### Id_rsa key
```
-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEApi/1V2hRf505MOUEAUyyz/m/qzov120lGYMEqNtMmUmuAGor
BylL49FcajsYB5pm9hUPK5GxnsyBFrum3jqKWHbr6+wRq8YKUbDp5Quxo8yWHpn9
KXMhsZZn4LpZO1kL6DR3ey5XD900+NmEGEqAh/Tlk2vSY7fGN3Qtlc1FPKlSrQEi
XgTbjbpzQEoGqc1E5IkuBG1n7T5BN54H3sSiGWhsiOgZ1po7uzLsdeHe2T8IVBAs
UObE7JH6+LXDmYQwxZXVmoFgkb7k0LnBQb1akKNXOBskIduMEzgdFlGF7C8YR8hC
kIkgyAWmvaPmjzQPrHJ9AZLLVar0wTc3QFwh6wIDAQABAoIBAQCKWiLGQfKXayzR
p9dNvayfuCv5QNfTYOoh8xFOAkQi2VQixEBOFfM4FnP5fHjk24YcGCwo+YIF0fsm
EdM570J9o4OFRWLwvk6Y88/E/5dD5m6Ty18XwuGqFq0kSf8/iUKAbi2KP2n7qw0O
nwd5sYyPozH9KSZeHgDG6dGJhPq/JGBQmqQdNuQUsB5O8fV37qQnAhqZTUHhsAmE
1P5EbZ90Apo+oSELcKOlJPssggXs3w3KRJUsgjOqyTmUTB0JlwG73akLz7CROZv0
J2qjr+HYzxsErZcKku1ZnG4JuJYof+9qhYSY7lyuTU5IMYCko00Fpv4m3j+OVX4I
JPpYlI4BAoGBANJBwxnAzYqjflYT1NwoSlgQ9D2c1S8NAOfiZsLu58onNatxW7f2
azdB/+FpuyCFJOFjXY4g24lVxxZX0u4Mt4qRDnYMeOeCBvAES5xgctdrCY2Fyyr3
pUcoGBLSR6s5QjOTe1PSgjYge96F4okmxAHI/ydyVpkKvhfTYTIYSO2DAoGBAMpX
vzZycp4vqG5B2jGqod+pgun4TJIkn1eVVeJ4vZhGuJ5Aj2MElhjw+dX2sYrokuUh
3A+eSr50uU4xc1gTYwsD4lbNR2a9PYZgTxHCYvXRcGeO1l/m5kdpgLLaAP8HgSBD
cTJ3OBA07fIocP62MfX5ILxYTGHUgs0su7uYnXV5AoGBAIdw92Yajg1V3mdCpSch
CSsL2NnrsmR5wvCdJkdCMKxHb8o93rB1m4FgEZ46RuHfAu/x221X+zPPvszEzEqu
hHlNkfw3cpbnauKoUbCtbK0Z9XBmFIdcOerJiCBvtt00qFGjGpnXjCuj50dkBZcG
EtN3j+3wOJqjkeq1LvJfNHNTAoGANXTNHXNK+KOamdZn8KslrNM5tNpWUF3AgwD+
+Z/wZuR4LcbcmspBZUF0n6RW713WQRaa7r1g/cQUmKXT1Tb5+ZUDHO+Kp4fjUzbq
bMSwJEU6rwE7fYag28jxqU6S6M1wvbdTloOMmiuBmXI5t/EmbddtYJTrSQU9sTra
NgtxvfECgYEAqzcFrCgL861rF6gfo+EBhpRRXEn0iP9PyPqDM1wEQMcdFBLkW3Eb
IEBXxZFmdB28G1HTseLJ58vsb4w2bzul3aNR4m4a77DlVi+pUDr6fAJKc2AQ2UgL
5/Y3TBKHLaVbAzepq9sOCy5cRI3GeUIiEPY9w8MhDg1rLJ+E//6VksQ=
-----END RSA PRIVATE KEY----
```
### passpharse password
'''
passpharse password is empty(you can directly press enter).

If it didn't work try password 'surya'.
'''
### id_rsa.pub key
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCmL/VXaFF/nTkw5QQBTLLP+b+rOi/XbSUZgwSo20yZSa4AaisHKUvj0VxqOxgHmmb2FQ8rkbGezIEWu6beOopYduvr7BGrxgpRsOnlC7GjzJYemf0pcyGxlmfgulk7WQvoNHd7LlcP3TT42YQYSoCH9OWTa9Jjt8Y3dC2VzUU8qVKtASJeBNuNunNASgapzUTkiS4EbWftPkE3ngfexKIZaGyI6BnWmju7Mux14d7ZPwhUECxQ5sTskfr4tcOZhDDFldWagWCRvuTQucFBvVqQo1c4GyQh24wTOB0WUYXsLxhHyEKQiSDIBaa9o+aPNA+scn0BkstVqvTBNzdAXCHr user@vinay
```
### grader password
```
surya
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
   
## Error by previous reviewer
It did'nt asked me to enter any passpharse.
I'm also including my private key in reviewer notes
![Screenshot (108).png](https://github.com/dasarisurya/Linux-Server-438/blob/master/Screenshot%20(108).png)
