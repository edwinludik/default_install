# Ubuntu

sudo apt-get update -y && sudo apt-get dist-upgrade -y && sudo apt-get install -y ufw byobu nano vim rsync  
byobu

## Dotnet Runtime 6
wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb

sudo apt update
sudo apt install -y aspnetcore-runtime-6.0
