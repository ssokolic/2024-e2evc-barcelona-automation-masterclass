If you have a Windows notebook you should enable the following Windows Features.

    - FeatureName : Microsoft-Windows-Subsystem-Linux

Switch to the Windows Store and install Ubuntu 20.22.1 LTS.

Install the following applications and tools (run the commands in order in the terminal):

sudo apt update && sudo apt upgrade
wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
sudo apt install python3
sudo apt install golang
sudo apt install python3-pip
sudo apt install pre-commit
pre-commit install

When the machine is prepared you can run PowerShell und access your Ubuntu instance by typing the command:

WSL
