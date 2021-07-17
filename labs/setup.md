# Blackhills Breaching the CLoud Course

## Docker
Next, let’s install Docker in our Kali VM. We’ll need it for one of the labs later on. In your fresh Kali VM run let’s first install dependencies
```
sudo apt -y install curl gnupg2 apt-transport-https software-properties-common ca-certificates 
```
Next we import Docker’s GPG key & add the Docker repo
```
curl -fsSL https://download.docker.com/linux/debian/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/docker-ce-archive-keyring.gpg
```
Install Docker
```
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io -y
```
Test it out by running the Docker “Hello World” container
```
sudo docker run hello-world
```
To start the service run:
```
sudo service docker start
```

## Pacu
```
cd ~/Desktop
sudo apt-get install python3-pip

git clone https://github.com/RhinoSecurityLabs/pacu
cd pacu
sudo bash install.sh
sudo pip3 install urllib3==1.25.10
```

## Terraform
```
cd ~/Downloads
unzip terraform*.zip
sudo mv ~/Downloads/terraform /usr/local/bin/terraform
```
## Windows 10 VM
```
("Skipped")
```
## Kali VM
```
(Skipped)
```

# Conclusion
We should have everything we will need for the training setup at this point. To review here are the following items you should now have ready for the class:

- Windows 10 VM with MSOL and Az PowerShell modules installed
- Password is “Passw0rd!”
- Kali VM with Docker installed
- Password set during installation
- A Microsoft Azure Account
- A Microsoft Azure Active Directory Account (Created by the Azure Account) 
- An Amazon AWS Account
- An Amazon Access key ID and Secret access key