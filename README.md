# udacity-linux-server-config

sudo apt-get update
sudo apt-get upgrade

ssh -i filename username@public ip -p 2200

wim.rtorr.com


    Go to the "SSH Keys" tab under your Lightsail Account page
    Select the Default option under your region and download the key pair file
        Will be a .pem file, ex. LightsailDefaultPrivateKey-us-west-2.pem
    Open up your terminal and navigate to the directory where the above file is stored
    Run chmod 600 [fileName] at the command line to restrict file permission so only you can read it
    Run ssh -i [fileName] [username]@[Public IP] to establish the connection to Lightsail
        Username and IP are available under the "Connect" tab on the Lightsail web dashboard for your resource

