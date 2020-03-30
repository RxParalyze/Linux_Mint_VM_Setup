# Linux_Mint_VM_Setup
This is a shell file to automagically set up a fresh Linux Mint and (hopefully) avoid the debug-blues. I personally love the Mint interface but there are some strange setup nuances that I hope I can help prevent. This script will likely run on most or all Linux OS's but its primary focus was Linux Mint (19.3 Tricia, Cinnamon Edition). 

Here's a list of the things that the script will try to install. If there's anything you don't want, just remove it before you run the script, or delete it afterwards.

git
apt-transport-https
ca-certificates
curl
gnupg-agent
software-properties-common
docker repo
make
maven
python3-setuptools
python3-pip
Openjdk-11
Packages from Microsoft
Microsoft Repo
VS Code
npm
Smurpho's nemo-actions and cinnamon-scripts
etc
