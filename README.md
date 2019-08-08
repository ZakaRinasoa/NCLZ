# NCLZ
NetCOreLinuxZar
https://dotnet.microsoft.com/download/linux-package-manager/ubuntu18-04/sdk-current

Register Microsoft key and feed
Before installing .NET, you'll need to register the Microsoft key, register the product repository, and install required dependencies. This only needs to be done once per machine.
Open a terminal and run the following commands:

wget -q https://packages.microsoft.com/config/ubuntu/18.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb

Install the .NET SDK
Update the products available for installation, then install the .NET SDK.
In your terminal, run the following commands:

sudo add-apt-repository universe
sudo apt-get install apt-transport-https
sudo apt-get update
sudo apt-get install dotnet-sdk-2.2
